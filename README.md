### Bolsa de Valores Bovespa 1994-2020
Projeto de Laboratório de Estrutura de Dados
Este projeto tem como objetivo aplicar e analisar diferentes algoritmos de ordenação em um conjunto de dados reais da BOVESPA (Bolsa de Valores do Brasil), com registros de ações no período de 1994 a 2020.

### 📁 Estrutura do Projeto
O projeto é dividido em três etapas principais:

### 1. Transformações no arquivo original
O arquivo original b3_stocks_1994_2020.csv contém dados como data, ticker, valores de abertura, fechamento, máximo, mínimo e volume negociado.

As seguintes transformações são realizadas:

Conversão da data para o formato DD/MM/AAAA → b3stocks_T1.csv

Filtro para manter apenas o registro com maior volume diário → b3stocks_F1.csv

Filtro para manter apenas registros com volume acima da média diária → b3stocks_T1_Filtrado.csv

### 2. Ordenações
Os algoritmos de ordenação utilizados são:

Insertion Sort

Selection Sort

Quick Sort (incluindo variação com Mediana de 3)

Merge Sort

Heap Sort

Counting Sort (limitado pelo tipo de dado)

Cada algoritmo realiza ordenações segundo os critérios:

Ordem alfabética dos tickers

Volume crescente

Variações diárias decrescentes (high - low)

Cada ordenação gera três arquivos .csv:

Caso médio

Melhor caso

Pior caso

### 3. Análise de desempenho
É feita a medição do tempo de execução de cada algoritmo em cada cenário.

### COMO EXECULTAR

Os resultados são apresentados em tabelas e gráficos no relatório técnico do projeto.

# Clone o repositório
git clone https://github.com/devjamilson/Projeto_1_Laboratorio_De_Estrutura_De_Dados

# Acesse a pasta do projeto
cd Projeto_2_Laboratorio_De_Estrutura_De_Dados

# Compile o código Java
javac Main.java

# Execute o projeto
java Main
 * LEMBRE de atualizar a pasta do projeto depois de compilar
 * 
