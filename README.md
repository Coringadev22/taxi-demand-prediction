# 🚕 Previsão de Demanda de Táxis por Hora

Projeto de ciência de dados para prever o número de corridas de táxi por hora na empresa fictícia **Taxi Corrida Maluca**. O objetivo foi construir um modelo capaz de prever a demanda com base em dados históricos e variáveis temporais, garantindo um RMSE menor que 48.

---

## 📊 Descrição do Projeto

Neste projeto, desenvolvemos um pipeline completo de previsão utilizando técnicas de análise de séries temporais, engenharia de features, validação cruzada e ajuste de hiperparâmetros com `GridSearchCV`.

---

## 🧪 Tecnologias Utilizadas

- Python 3.10+
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Estrutura do Projeto

├── data/
│ └── taxi.csv # Dataset original
├── notebook/
│ └── Sprint.ipynb # Notebook com todo o processo
├── requirements.txt # Dependências do projeto
├── README.md # Você está aqui


---

## ⚙️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/taxi-demand-prediction.git
   cd taxi-demand-prediction

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
jupyter notebook notebook/Sprint.ipynb


📈 Resultados
Melhor modelo: Random Forest Regressor

Melhor RMSE validado: 25.79 (com TimeSeriesSplit + GridSearchCV)

Meta do projeto (RMSE < 48): ✅ Atingida

📌 Insights Importantes
Foram criadas variáveis como hour, dayofweek, lag, rolling_mean.

A divisão temporal dos dados respeitou a ordem natural do tempo.

A validação cruzada foi feita com TimeSeriesSplit para simular múltiplos cenários reais.

O modelo final está pronto para produção e pode ser integrado via API futuramente.

✍️ Autor
Lucas Coelho
📍 Empreendedor e Cientista de Dados Júnior
📆 Junho de 2025


