# 🌍 Analisando a taxa de mortalidade ao longo dos anos (1970 - 2010)

Bem-vindo(a) ao repositório do meu projeto de Análise de Dados! Este projeto explora dados históricos da Carga Global de Doenças, com base nas estimativas do Instituto de Métricas e Avaliação de Saúde (IHME), abordando as taxas de mortalidade globais ao longo de quatro décadas.

## 🎯 Objetivo do Projeto
Investigar o número de mortes e a taxa de mortalidade a cada 100.000 habitantes, explorando as relações entre diferentes países, faixas etárias e sexos. O projeto culmina na criação de um **Dashboard Interativo** para facilitar a visualização dos dados por qualquer usuário.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python** (Linguagem principal)
* **Google Colab** (Ambiente de desenvolvimento)
* **Pandas** (Limpeza, manipulação e agrupamento de dados)
* **Matplotlib & Seaborn** (Criação de visualizações e gráficos estatísticos)
* **Streamlit** (Desenvolvimento do Dashboard interativo)

## 📊 Principais Insights e Descobertas
Durante a Análise Exploratória de Dados (EDA), respondemos a perguntas cruciais e descobrimos que:
- 🏆 **Pior Cenário Histórico:** O **Mali** apresentou a maior média de taxa de mortalidade entre os 187 países analisados (16.663 mortes por 100.000 hab.).
- 🌟 **Maior Evolução:** As **Maldivas** tiveram a melhoria mais significativa, reduzindo drasticamente sua taxa de mortalidade entre 1970 e 2010.
- 🇧🇷 **Foco no Brasil:** A faixa etária com o maior número absoluto de mortes no Brasil é a de **80+ anos** (somando mais de 793 mil mortes no período, sendo a maior parte na última década). Além disso, a evolução temporal mostra um número consistentemente maior de mortes masculinas em comparação às femininas.

## 🚀 Como executar este projeto

1. Abra o arquivo .ipynb no Google Colab ou no seu ambiente Jupyter local.

3. Faça o upload do arquivo da base de dados (o CSV baixado do Tableau Free Public Datasets) para o seu ambiente.

4. Execute as células sequencialmente.

5. Para o Dashboard: Na última etapa do notebook, o código gera um arquivo app.py e utiliza o localtunnel para disponibilizar o painel do Streamlit na web. Siga as instruções impressas no terminal do Colab para acessar o link gerado com a senha (IP) fornecida.

📝 Dicionário de Dados
 A base contém 58.905 registros totalmente preenchidos, com as seguintes colunas principais:
* `Country Name`: Nome do país analisado.
* `Year`: Ano do registro (1970, 1980, 1990, 2000, 2010).
* `Age Group`: Faixa etária.
* `Sex`: Gênero (Male, Female, Both).
* `Number of Deaths`: Número absoluto de mortes.
* `Death Rate Per 100,000`: Taxa proporcional de mortes a cada 100 mil habitantes.

[Link para o dataset]([https://www.tableau.com/learn/articles/free-public-data-sets](https://ghdx.healthdata.org/record/ihme-data/gbd-2010-mortality-results-1970-2010))
