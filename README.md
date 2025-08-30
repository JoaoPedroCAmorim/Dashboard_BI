# Análise de Vendas e Devoluções - Dashboard de Vendas

Este projeto apresenta um **Dashboard Interativo de Vendas** desenvolvido para monitorar e analisar o desempenho comercial de uma empresa. O painel foi criado para fornecer insights estratégicos para as áreas de **Finanças, Marketing e Comercial**, permitindo uma visão detalhada sobre receitas, indicadores de performance (KPIs) e o volume de devoluções. Este Dashboard foi criado no curso da Hashtag Treinamentos.

## Funcionalidades Chave

O dashboard é dividido em três painéis principais para uma análise completa:

* **Painel Geral:** Visão global do negócio, incluindo vendas totais, faturamento total, lucro total e margem de lucro.
* **Painel de Indicadores (KPIs):** Focado em métricas de performance, como marcas e produtos mais vendidos, crescimento de vendas e lojas que tiveram melhor desempenho.
* **Painel de Devoluções:** Análise detalhada de produtos devolvidos, impacto financeiro e % de devoluções.

## Tecnologias e Ferramentas

* **Power BI:** Ferramenta principal utilizada para a criação do dashboard.
* **Power Query:** Para extração, tratamento e transformação dos dados.
* **DAX:** Para criação de medidas e colunas calculadas.

## Como Visualizar

1. Tela de Abertura: Capa de apresentação, o botão "Ir para o Dashboard" facilita a navegação entre as paginas.
<img width="1457" height="819" alt="image" src="https://github.com/user-attachments/assets/f38a6f20-1e55-46ad-971a-e92c484f1b99" />
2. Painel de Vendas Gerais: No segundo painel, mostra as informações de faturamento, lucro, total de vendas e margem de lucro. Além disso, foram utilizados gráficos de coluna e pizza para facilitar a visualização dos dados.
<img width="1462" height="784" alt="image" src="https://github.com/user-attachments/assets/adb0d2e7-b1db-4d81-b4c4-528a3c25cb31" /> 
Painel de Indicadores de Desempenho: No terceiro painel, mostra a marca e produtos por marca mais vendidos, além de fornecedor um texto explicativo com o produto e loja que obtiveram mais vendas no período solicitado.
<img width="1456" height="801" alt="image" src="https://github.com/user-attachments/assets/227caf1a-b342-4003-b83f-15d33764ac86" />
Painel de Devoluções: No último painel, é muito parecido com o primeiro porém traz as informações de produtos devolvidos. A principal diferença é um mapa que mostra os países e continentes que tiveram maior devolução de produtos.
<img width="1458" height="798" alt="image" src="https://github.com/user-attachments/assets/30216c40-18e7-44ad-8643-f5d47cfa6c20" />

## Estrutura do Projeto

A construção deste dashboard seguiu os seguintes passos:

1.  **Coleta e Limpeza de Dados:** Importação e tratamento de dados de vendas e devoluções no Power Query.
2.  **Modelagem de Dados:** Criação de um modelo de dados otimizado, estabelecendo relacionamentos entre tabelas, seguindo no formato de star schema, a tabela fato no centro e as tabelas dimensão em volta.
3.  **Cálculos e Medidas:** Desenvolvimento de medidas DAX para KPIs e métricas personalizadas.
4.  **Visualização e Design:** Criação de gráficos e painéis interativos para apresentar os dados de forma clara e intuitiva.
