Este projeto tem como objetivo realizar uma análise exploratória e preditiva dos preços do petróleo Brent, utilizando técnicas de ciência de dados e machine learning. O foco é identificar tendências, padrões históricos e prever preços futuros com base em dados disponíveis.

## Objetivos  

1. **Explorar os dados históricos** do preço do petróleo Brent e identificar padrões sazonais e tendências.  
2. **Visualizar os dados** para melhor compreensão das flutuações e correlações com fatores externos.  
3. **Aplicar técnicas de machine learning** para criar modelos de previsão do preço.  

## Estrutura do Projeto  

```plaintext
.
├── datasets/               # Arquivos de dados brutos e processados
├── brent_oil.ipynb          # Notebook Jupyter usados para a análise
├── README.md           # Documentação do projeto
```

## Tecnologias Utilizadas
- Linguagem: Python 3.9+
- Bibliotecas Principais:
  - pandas - Manipulação e limpeza de dados
  - matplotlib e seaborn - Visualização de dados
  - prophet - Modelagem preditiva
  - statsmodels - Análise estatística e de séries temporais
  - Jupyter Notebook - Documentação e análise interativa
  - Dados
    Os dados foram obtidos de [http://www.ipeadata.gov.br/ExibeSerie.aspx?module=m&serid=1650971490&oper=view], contendo informações históricas dos preços do petróleo Brent.

## Resultados
- Análise Exploratória:
- Identificação de tendências anuais e eventos que influenciaram o preço do petróleo.
- Correlação entre o preço do petróleo e indicadores econômicos globais.
- Modelos Criados:
- Modelo de séries temporais (Prophet) para previsão de longo prazo.
