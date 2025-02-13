### **README - Projeto Transfer Learning: Coca-Cola vs. Pepsi (DIO)**

#### **Descrição:**
Este projeto aplica Transfer Learning com a rede VGG16 para classificar imagens de Coca-Cola e Pepsi. 
Foi desenvolvido no Google Colab e segue as exigências do enunciado para Prova de Conceito (Prova Final).

#### **Estrutura do Projeto:**
1. **Configuração do Ambiente:** Importação de bibliotecas e montagem do Google Drive.
2. **Carregamento do Dataset:** Uso de `image_dataset_from_directory` com divisão automática em treino e validação.
3. **Modelo com VGG16:** Transfer Learning com camadas congeladas e nova camada densa personalizada.
4. **Treinamento:** Execução por 10 épocas com `adam` e `sparse_categorical_crossentropy`.
5. **Desempenho:** Gráfico comparativo de acurácia entre treino e validação.
6. **Salvamento:** Exportação do modelo treinado para o Google Drive.
7. **Publicação:** Envio do projeto para o GitHub da DIO.

#### **Como Executar:**
- Abra o projeto no Google Colab.
- Certifique-se de ativar a GPU em *Runtime > Change runtime type > GPU*.
- Ajuste o caminho do dataset se necessário.
- Execute as células sequencialmente.

#### **Requisitos:**
- Python 3
- TensorFlow 2.x
- Google Colab
- Conta no GitHub
