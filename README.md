# Predição de Churn com Regressão Logística

Este projeto utiliza Machine Learning para identificar a probabilidade de cancelamento de clientes (Churn), permitindo que a empresa tome ações preventivas para retenção.

## 📊 Performance do Modelo

O modelo foi avaliado com foco em métricas que garantem a confiabilidade da predição para o negócio. O alto valor de **AUC-ROC** indica uma excelente capacidade de distinção entre clientes que cancelam e clientes que permanecem.

| Métrica | Resultado | Significado |
| :--- | :--- | :--- |
| **Acurácia** | 0.81 | Performance geral de acertos. |
| **AUC-ROC** | 0.91 | Capacidade do modelo de separar as classes (Excelente). |
| **Recall** | 0.75 | 75% dos clientes em Churn são identificados pelo modelo. |
| **Precisão** | 0.82 | Quando o modelo prevê Churn, ele acerta em 82% das vezes. |
| **F1-Score** | 0.79 | Equilíbrio entre Precisão e Recall. |



## 💡 Insights Estratégicos (Visão de Negócio)

A partir da análise dos dados e do comportamento do modelo, identificamos:
* **Fator de Risco:** Clientes com comportamentos similares às Variáveis 1 e 3 possuem 0.91 de probabilidade de saída se não houver intervenção.
* **Qualidade do Alerta:** Com 82% de Precisão, o time de marketing pode investir em cupons de desconto para os clientes sinalizados sem medo de desperdiçar recursos com quem não ia sair.
* **Estratégia Recomendada:** Focar em aumentar o "Recall" em próximas versões para capturar os 25% de clientes que o modelo ainda não consegue prever.

## ⚙️ Pipeline Técnico (Maturidade do Projeto)

Para garantir um código limpo e profissional, o projeto seguiu estas etapas:
1. **EDA:** Análise exploratória para entender a distribuição das classes.
2. **Pré-processamento:** Padronização com `StandardScaler` (essencial para que variáveis com números grandes não "viciem" o modelo).
3. **Tratamento de Dados:** Uso de `class_weight='balanced'` para lidar com dados onde há poucos cancelamentos em relação ao total.
4. **Modelagem:** Implementação de Regressão Logística.
5. **Serialização:** Modelo salvo em formato `.pkl` (Pickle) para ser usado em aplicações reais sem precisar treinar novamente.

## 📂 Estrutura de Arquivos
* `projeto_churn.ipynb`: Código com o treinamento e avaliação.
* `modelo_final.pkl`: O modelo treinado pronto para uso.
* `requirements.txt`: Bibliotecas necessárias para rodar o projeto.
---
✨ Conecte-se comigo no LinkedIn: https://www.linkedin.com/in/luana-reis-53552626a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
