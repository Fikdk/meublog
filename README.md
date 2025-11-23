# Meublog - Atividade sobre APIs
### Este repositório contém as três atividades desenvolvidas em Python envolvendo consumo de APIs, visualização de dados e análise estatística, utilizando bibliotecas como requests, plotly, plotnine e folium.

### Atividade 01 – Cotação do Dólar por Período
Objetivo: Desenvolver uma rotina que receba um período no formato "MMYYYY" e exiba um gráfico com a cotação do dólar nesse mês.

**O que foi implementado:**
```
Uso da API do Banco Central (PTAX).
A função converte o mês/ano em data inicial e final automaticamente.
Quando a data não possui cotação (fim de semana/feriado), o sistema busca o último dia útil anterior.
Geração de gráfico de linha mostrando a variação diária usando Plotly.
```

**Tecnologias usadas:**
```
requests
datetime
plotly
```

### Atividade 02 – Monitoramento de Frota de Ônibus (SPTrans)
Objetivo: Era criar um mapa informando: paradas de uma linha de ônibus e a posição em tempo real dos ônibus em operação, se possível.

**O que foi implementado:**
```
Autenticação na API Olho Vivo da SPTrans.
Busca das paradas da linha.
Consumo da API de posição dos ônibus em tempo real.
Criação de um mapa interativo usando Folium.
Pins vermelhos = paradas / Pins azuis = ônibus em movimento.
O mapa é exibido diretamente no notebook/página (sem salvar arquivo).
```

**Tecnologias usadas:**
```
requests
folium
IPython.display
```

### Atividade 03 – Regressão Linear
Objetivo: Aplicar regressão linear utilizando a forma matricial para analisar a relação entre os anos de estudo (X) e o Salário (Y).

**O que foi implementado:**
```
Leitura dos arquivos x.txt e y.txt.
Cálculo dos coeficientes da reta (a e b) via fórmula matricial.
Geração de gráfico com os pontos e a reta de regressão.
Visualização do resultado utilizando plotnine.
```

**Tecnologias usadas:**
```
numpy
pandas
plotnine
```

### Tecnologias Utilizadas para a realização do projeto:
```
Python 3
Requests
Plotly
Folium
Pandas
Numpy
Plotnine
```
**Aluno: Luigi Del Vecchio**
**RA: 056644**
