# olist-data-science-analysis
Análise de Dados - E-commerce Olist (Brasil)

Este projeto apresenta uma análise exploratória de dados (EDA) do dataset público de e-commerce da Olist, disponível no Kaggle. O objetivo é extrair insights sobre o comportamento de compra, logística e performance de categorias de produtos.
📌 Visão Geral do Projeto

O projeto foi desenvolvido em Python, utilizando Jupyter Notebook, com foco em limpeza de dados, tratamento de séries temporais e análise de correlações logísticas.
🛠️ Tecnologias e Bibliotecas

    Python 3.x

    Pandas: Manipulação e limpeza de dados.

    Seaborn / Matplotlib: Visualização de dados e mapas de calor.

    NumPy: Suporte matemático.

📂 Estrutura dos Dados

A análise integra múltiplos datasets, incluindo:

    Clientes e suas localizações.

    Itens dos pedidos e preços.

    Datas de pagamento e status de entrega.

    Informações sobre dimensões e categorias dos produtos.

🚀 Etapas Realizadas

    Limpeza de Dados: Filtragem de pedidos entregues e tratamento de valores ausentes.

    Conversão de Tipos: Transformação de colunas de data para o formato datetime para cálculos de performance.

    Engenharia de Variáveis:

        Criação da métrica tempo_entrega (diferença entre compra e entrega).

        Extração de sazonalidade (dia da semana e mês da compra).

    Análise de Correlação: Estudo da relação entre valor do frete, peso do produto e tempo de entrega.

📈 Principais Insights

    Sazonalidade: Identificação de picos de vendas em dias específicos da semana (Segunda e Terça-feira).

    Faturamento por Categoria: Destaque para as categorias "Beleza & Saúde" e "Relógios & Presentes".

    Logística: Análise de correlação indicando que o valor do frete possui uma relação positiva moderada com o tempo de entrega no cenário analisado.

📝 Como Executar

    Clone o repositório:
    Bash

git clone https://github.com/seu-usuario/nome-do-repositorio.git

Certifique-se de ter as dependências instaladas:
Bash

pip install pandas seaborn matplotlib

Abra o arquivo ecommerceolist.ipynb em seu ambiente Jupyter ou VS Code.
