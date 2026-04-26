# Projeto Final - Ciencia de Dados com Python

## Descricao

Este projeto final usa o dataset real **Brazilian Cities** para analisar desigualdades entre municipios brasileiros e propor uma lista de priorizacao para acoes de desenvolvimento humano.

O problema formulado e:

> Quais municipios brasileiros devem ser priorizados em acoes de desenvolvimento considerando baixo IDHM, populacao afetada e PIB per capita?

## Estrutura

```text
projeto-final/
├── datasets/
│   └── brazilian_city.csv
├── notebook/
│   └── projeto_final.ipynb
└── README.md
```

## Links

- Notebook do projeto: [`notebook/projeto_final.ipynb`](notebook/projeto_final.ipynb)
- Dataset utilizado: [`datasets/brazilian_city.csv`](datasets/brazilian_city.csv)
- Documentacao do pandas: https://pandas.pydata.org/docs/
- Documentacao do seaborn: https://seaborn.pydata.org/
- Documentacao do matplotlib: https://matplotlib.org/stable/

## Como executar

1. Abra a pasta do curso no VS Code.
2. Instale as bibliotecas principais, caso ainda nao tenha:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Abra o arquivo `projeto-final/notebook/projeto_final.ipynb`.
4. Execute as celulas em ordem, de cima para baixo.

## Entregaveis

- Dataset real incluido na pasta `datasets`.
- Perguntas de negocio documentadas no notebook.
- Visualizacoes criadas com matplotlib e seaborn.
- Insights e conclusoes ao final da analise.
