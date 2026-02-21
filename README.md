# Desafio Técnico Individual - Liga de IA (CIn-UFPE)

Este repositório contém a solução desenvolvida para o desafio de detecção de fraudes, com ROC AUC de **0.98948**.

## 🚀 Como executar
1. Clone o repositório: `git clone https://github.com/Guilherme-Muniz/Desafio_individual_ligia.git`
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o notebook em `notebooks/final_model.ipynb` para gerar as predições.

## 🧠 Metodologia
* **Modelo**: XGBoost com ajuste fino de hiperparâmetros (Learning Rate: 0.004, Depth: 8).
* **Engenharia de Recursos**: Criação de colunas temporais (Hour) e normalização logarítmica (Log_Amount).
* **Validação**: Cross-Validation com 10 folds para garantir estabilidade.