# 📊 Previsão de Churn (Cancelamento) com Regressão Logística

Este projeto utiliza **Machine Learning** para identificar quais clientes de uma empresa de telecomunicações têm maior probabilidade de cancelar seus serviços. O objetivo é permitir que a empresa tome ações preventivas de retenção.

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Pandas & Numpy:** Manipulação de dados.
* **Scikit-Learn:** Construção do modelo de Regressão Logística.
* **Matplotlib & Seaborn:** Visualização de dados e métricas.

## 🧠 O Projeto
A Regressão Logística foi escolhida por ser um modelo robusto e de fácil interpretação. 

### Etapas Principais:
1. **Análise de Dados:** Identificamos os perfis de clientes que mais cancelam.
2. **Tratamento:** Lidamos com dados faltantes e transformamos categorias em números.
3. **Equilíbrio:** Usamos técnicas para o modelo não ignorar a minoria (os que cancelam).
4. **Avaliação:** Focamos na curva **ROC-AUC** para garantir que o modelo saiba separar bem os clientes fiéis dos que estão em risco.

## 📈 Resultados obtidos
* **Acurácia:** [COLOQUE AQUI O SEU VALOR]%
* **AUC:** [COLOQUE AQUI O SEU VALOR]
* **Principais Descobertas:** Clientes com contratos mensais e contas mais altas são os mais propensos a sair.

## 🚀 Como rodar o projeto
1. Clone o repositório.
2. Instale as bibliotecas: `pip install -r requirements.txt`.
3. Execute o notebook na pasta `notebooks/`.

---
Feito por [SEU NOME] - [Link do seu LinkedIn]