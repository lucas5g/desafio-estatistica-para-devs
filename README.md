# Desafio - Estatística para Devs

Este projeto apresenta uma resolução simples de um desafio de análise de vendas com Python.

No notebook `main.ipynb`, os dados são organizados em um `DataFrame` com `pandas`, a média das vendas é calculada e os resultados são visualizados com gráficos de barras e de linhas usando `matplotlib`.

## Objetivo

Trabalhar um dicionário de faturamento para:

1. Gerar um `DataFrame`.
2. Calcular a média das vendas.
3. Criar um gráfico de barras com mês de referência e valor.
4. Criar um gráfico de linhas com mês de referência e valor.

## Tecnologias

- Python 3.14
- pandas
- matplotlib
- Jupyter Notebook

## Estrutura

- `main.ipynb`: notebook principal com a resolução do desafio.
- `Pipfile`: dependências do projeto.
- `Pipfile.lock`: versões travadas das dependências.

## Como executar

### 1. Instalar dependências

Se você usa `pipenv`:

```bash
pipenv install
```

### 2. Ativar o ambiente virtual

```bash
pipenv shell
```

## O que foi desenvolvido

O notebook contém:

- explicação em markdown antes de cada etapa do código;
- criação do `DataFrame` a partir de um dicionário de faturamento;
- cálculo da média da coluna `valor`;
- gráfico de barras vertical;
- gráfico de linhas.

## Resultado

Como resultado, o projeto entrega uma análise simples e objetiva dos dados de faturamento, apresentando a média das vendas e duas visualizações gráficas para facilitar a interpretação das informações.
