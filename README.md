# 📈 Crypto Price Prediction with Deep Learning

Este repositório contém modelos de previsão de preços de criptomoedas utilizando redes neurais LSTM. O objetivo é analisar dados históricos de diferentes criptomoedas e prever suas tendências futuras.

## 📌 Criptomoedas incluídas
- 🐶 **Dogecoin (DOGE)**
- 🐕 **Shiba Inu (SHIBA)**
- 🚀 **Floki Inu (FLOKI)**
- ❌ **XEC (eCash)**

## 🛠 Tecnologias utilizadas
- Python
- TensorFlow / Keras
- Pandas & NumPy
- Scikit-learn
- Matplotlib

## 📊 Como funciona
1. **Carregamento dos dados**: O modelo lê dados históricos de preços.
2. **Pré-processamento**: Normalização dos dados para otimizar o treinamento.
3. **Treinamento com LSTM**: Rede recorrente treinada para prever tendências futuras.
4. **Métricas de avaliação**: Cálculo de MAE, MSE, RMSE e R².
5. **Previsão futura**: Geração de previsões para os próximos 90 dias.

## 🚀 Como executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/crypto
   ```
2. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib tensorflow scikit-learn
   ```
3. Execute um dos notebooks (`doge.ipynb`, `shiba.ipynb`, etc.) no Jupyter Notebook ou Google Colab.

## 📈 Exemplo de previsão
O modelo gera previsões futuras com base nas últimas observações:
```plaintext
Previsões futuras para 90 dias:
[[0.0732]
 [0.0741]
 [0.0765]
 ...
 [0.0912]]
```

## 📬 Contato
Caso tenha dúvidas ou sugestões, sinta-se à vontade para abrir uma issue ou entrar em contato!

---
⭐ Se você gostou deste projeto, não esqueça de dar um **star** no repositório!
