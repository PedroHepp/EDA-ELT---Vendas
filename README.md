# 📊 Análise de Vendas - DataSmart

Este projeto apresenta uma análise exploratória de dados (EDA) e tramento de dados sobre vendas realizadas por uma empresa fictícia chamada **DataSmart**. A proposta é transformar dados brutos em informações úteis para a tomada de decisões, respondendo a perguntas estratégicas de negócio com base nos dados.

## 🧠 Perguntas Respondidas na Análise

1. Quais são os top 5 produtos mais vendidos em quantidade e faturamento?
2. Existe correlação entre preço unitário e quantidade vendida?
3. Qual categoria gera maior receita e qual gera maior volume de vendas?
4. Quais clientes compram com mais frequência?
5. Como se distribui o faturamento por estado?
6. Qual método de pagamento é mais utilizado e qual gera maior receita?

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly Express

## 💾 Otimização de Memória

Durante o processo de tratamento de dados, foi realizada uma otimização completa nos tipos de dados do dataframe, o que resultou em uma redução de 54% no uso de memória. Essa etapa foi essencial para tornar o processamento mais eficiente e reduzir o custo de armazenamento ao salvar os dados em formato Parquet, que além de compacto, preserva os tipos de dados utilizados.

## 📁 Estrutura do Projeto

```
📦analise-vendas-datasmart
 ┣ 📊 Análise_Vendas.ipynb            # Notebook com a análise de vendas e resposta das perguntas
 ┣ 📊 EDA_ETL_Vendas_Online.ipynb     # Notebook principal com toda a análise exploratória e tratamento de dados
 ┣ 📄 README.md                       # Documentação do projeto
 ┣ 🖼️ boxplots.png                    # Imagem dos boxplots gerados pelo plotly já que só aparece localmente por ser interativo
 ┣ 📂 vendas_online.csv               # dataset inicial sem tratamentos
 ┗ 📂 vendas_online_tratada.parquet   # dataset tratado
```

## 📈 Exemplos de Insights

- Produtos com maior volume de vendas podem não ser os que mais geram receita.
- A categoria "Livros" se destaca tanto em receita quanto em volume.
- Estados com maior população nem sempre são os que mais consomem.
- Correlação entre preço e volume ajuda a entender elasticidade da demanda.
