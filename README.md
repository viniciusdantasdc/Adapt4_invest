## Adapt4_invest

### MT5
script para bot de operações financeiras

### iniciando python em terminal

[config python](https://docs.github.com/pt/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/setting-up-your-python-project-for-codespaces)

### insall pandas/matplotlib/yfinance

#### registrando as bibliotecas

pip freeze > requirements.txt

### coins digitais

[bitcoin](https://www.coingecko.com/pt/api/pricing)

### médias em python

```
mme = (price1_mme_anterior) * (2/n + 1) + mme_anterior
n   = periódos
mme = média móvel exponencial
```

medias simples == .rolling
medias expon == .ewn

[Normalização](https://medium.com/ipnet-growth-partner/padronizacao-normalizacao-dados-machine-learning-f8f29246c12)

df[] = df.groupby('col').df[].pct_change()
df[] = df.groupby('col').df[].shift(-1)
df[] = df.groupby('data')["pontos"].rank(ascending = True (decrescente) | False (crescente)
df[df['data'] == "yyyy-mm-dd"].sort_values('rank_final').head(5)

analise >> volume de vendas e compras acumulada
analise >> soma das variações do volume (sinóide)
df[coluna] = Serie = var.to_frame()
frame[] = (1 + frame[]).cumprod() - 1
qs.extend+pandas()
frame.index = pd.to_datatime(frame.index)


### function para series temporais

[maniputando series](https://www.datacamp.com/pt/tutorial/pandas-resample-asfreq)

[GRÍFICO EM CANVA+PYTHON](https://usandopy.com/humix/video/Epl9wOYQYH2)
