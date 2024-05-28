# Análise das Exportações do Brasil para a França (2016-2020)

Este projeto realiza uma análise das exportações do Brasil para a França no período de 2016 a 2020. Utilizando a linguagem Python e o Jupyter Notebook, o objetivo é responder a algumas perguntas chave sobre essas exportações.

## Instruções de Uso

### 1. Carregamento da Base de Dados

A base de dados utilizada neste projeto está armazenada no arquivo `exportacoes_franca.csv`. Para carregar e filtrar a base de dados, siga os seguintes passos:

1. Leia o arquivo CSV contendo os dados de exportação.
2. Filtre os dados para considerar apenas os registros do bloco econômico 'Europe'.
3. Exiba a tabela resultante.

### 2. Informações Gerais

Para obter uma visão geral dos dados, incluindo o número de entradas e tipos de colunas.
print(tabela.info())

### 3. Evolução das Exportações ao Longo dos Anos

Para analisar como as exportações para a França evoluíram em termos de valor (US$ FOB) ao longo dos anos:

1. Agrupe os dados por ano e calcule a soma dos valores de exportação.
2. Formate os valores de exportação para uma exibição mais legível.
3. Exiba a tabela com a evolução anual das exportações.

### 4. Produtos Mais Exportados

Para identificar os produtos mais exportados (em US$ FOB) ao longo do período analisado:

1. Agrupe os dados pela descrição dos produtos e calcule a soma dos valores de exportação.
2. Ordene os produtos pelo valor de exportação em ordem decrescente.
3. Exiba a tabela com os produtos mais exportados.

### 5. Cidade com Maior Exportação em 2020

Para descobrir qual cidade brasileira mais exportou para a França em 2020:

1. Filtre os dados para o ano de 2020.
2. Agrupe os dados por cidade e calcule a soma dos valores de exportação.
3. Ordene as cidades pelo valor de exportação em ordem decrescente.
4. Exiba a tabela com as cidades que mais exportaram em 2020.

### 6. Exportações das Maiores Cidades em 2020

Para analisar os produtos exportados pelas duas maiores cidades exportadoras em 2020:

1. Filtre os dados para as maiores cidades exportadoras no ano de 2020.
2. Agrupe os dados pela descrição dos produtos e calcule a soma dos valores de exportação.
3. Ordene os produtos pelo valor de exportação em ordem decrescente.
4. Exiba a tabela com os produtos exportados pelas maiores cidades.

## Requisitos

- Python 3.x
- Pandas
- Jupyter Notebook

## Como Executar

1. Clone o repositório.
2. Instale as dependências necessárias.
3. Abra o Jupyter Notebook e execute as células de código conforme necessário.

## Contribuição alunos da UNIBH
Ana Luiza Da Silva Ferreira
Gustavo Antonionni Carvalho
Thiago Augusto Jardim
Wallysson Vieira Magalhães
