# Testando ETL Através do Google Colab

![Print Google Colab](https://i.imgur.com/cy216EX.png)

Este repositório contém um `Script Python` para análise de vendas de duas filiais de uma empresa. Os dados foram obtidos a partir de arquivos CSV e Excel.

## Dados Obtidos

Os dados das vendas das filiais foram extraídos de dois arquivos:

- **vendas_filial1.csv**: Contém os dados de vendas da Filial 1 em formato CSV.
- **vendas_filial2.xlsx**: Contém os dados de vendas da Filial 2 em formato Excel.

## Processo de Análise

O código utiliza a biblioteca pandas para ler os arquivos de dados, calcular o valor total das vendas e imprimir os resultados na saída padrão.

## Estrutura do Código

O código está estruturado da seguinte forma:

1. **Importação de Bibliotecas**: Importa a biblioteca pandas.
2. **Extração de Dados**: Lê os dados dos arquivos CSV e Excel utilizando as funções `pd.read_csv()` e `pd.read_excel()`.
3. **Transformação de Dados**: Calcula o valor total das vendas multiplicando a quantidade vendida pelo preço unitário e adiciona uma nova coluna "Valor Total" aos dataframes.
4. **Saída de Resultados**: Imprime os dados das vendas de cada filial, incluindo a nova coluna "Valor Total".

## Como Executar

Para executar o script, você precisa ter Python e a biblioteca pandas instalados em seu ambiente. Em seguida, basta executar o código Python fornecido neste repositório.

Outra forma de executar é apenas ir no arquivo `EXEMPLO_ETL.ipynb` e clicar no ícone `Open in Collab`.
