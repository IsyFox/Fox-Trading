# Fox Trading

Plataforma em português para aprender forex: curso completo (price action, SMC, pontos de entrada, gestão de risco, análise fundamental e transição do Boom & Crash), calculadoras, cenários reais e simulador com dados históricos reais (2015–2022), incluindo dias de NFP.

## Como abrir

Site estático: basta publicar com GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

Para usar no computador sem internet, sirva a pasta com um servidor local, por exemplo:

```
python -m http.server 8000
```

e abra `http://localhost:8000`. Abrir o `index.html` com duplo clique não carrega as sessões do simulador, porque o navegador bloqueia a leitura da pasta `data` a partir de ficheiros locais.

## Dados

Preços históricos (MT5) de [ejtraderLabs/historical-data](https://github.com/ejtraderLabs/historical-data), convertidos para a hora de Maputo (UTC+2).

Material educativo. Negociar forex com alavancagem envolve risco elevado de perda.
