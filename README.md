### 📊 Análise de Evasão de Clientes (Churn) – TelecomX

**Objetivo**
Analisar os dados de clientes da TelecomX para identificar os principais fatores que levam à evasão (Churn). O objetivo é traçar o perfil do cliente em risco e fornecer insights estratégicos para a retenção de clientes.

**🔍 Indicadores Analisados**
* **Distribuição de Churn:** Proporção de clientes que cancelaram o serviço.
* **Churn por Perfil:** Análise da evasão por gênero, senioridade e tipo de contrato.
* **Churn por Serviço:** Relação da evasão com serviços de segurança online, backup, streaming, etc.
* **Análise Numérica:** Relação da evasão com o tempo de contrato (`tenure`), gastos mensais e gastos totais.

**📌 Principais Conclusões**
* A taxa de evasão está fortemente associada a clientes com **contratos mensais**.
* Clientes com **pouco tempo de serviço** (`tenure` baixo) são o grupo mais vulnerável ao churn.
* O uso de **cheques eletrônicos** como método de pagamento tem uma alta correlação com a evasão de clientes.
* Não há diferença significativa na taxa de churn entre gêneros.

**Recomendação:** A empresa deve focar seus esforços de retenção em clientes novos e com planos mensais, incentivando a migração para contratos de longo prazo.

**🛠️ Como Utilizar o Projeto**
1.  Acesse o repositório no GitHub.
2.  Abra o notebook no **Google Colab** ou **Jupyter Notebook**.
3.  Execute as células para visualizar:
    * Gráficos comparativos de churn por diferentes perfis de clientes.
    * Análises detalhadas da distribuição de variáveis numéricas.
    * Conclusões e recomendações estratégicas.

**💡 Insights Obtidos**
* Como identificar os principais drivers de churn em uma base de clientes.
* Quais métricas são mais relevantes para entender o comportamento de evasão.
* Como transformar análises de dados em ações estratégicas de retenção.

**👨‍💻 Tecnologias Utilizadas**
* **Python:** Pandas, Matplotlib, Seaborn
* **Ferramentas:** Google Colab
* **Metodologia:** Análise de Dados Exploratória (EDA) e Visualização de Dados

**Autor:** [Vitor Oliveira]
