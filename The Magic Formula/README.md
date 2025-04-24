# 📊 Magic Formula Backtesting - B3 (2019–2025)

Este projeto aplica a **Fórmula Mágica de Joel Greenblatt** ao mercado brasileiro, utilizando dados reais de empresas listadas na **B3** entre 2019 e 2025 (YTD). O objetivo é avaliar o desempenho da estratégia com diferentes tamanhos de portfólio, comparando os resultados com o índice **IBOVESPA**.

## 🧠 Sobre a Estratégia

A Fórmula Mágica busca identificar ações "baratas e boas" com base em dois indicadores fundamentais:

- **ROIC (Retorno sobre o Capital Investido)** – mede a qualidade da empresa.
- **Earnings Yield (inverso do EV/EBIT)** – mede o quanto a ação está "barata".

As empresas são ranqueadas com base em uma combinação desses dois fatores, e as mais bem colocadas são selecionadas para compor os portfólios.

## 🔬 O que foi testado?

Foram simuladas carteiras com diferentes quantidades de ativos:

- 1 ativo
- 5 ativos
- 20 ativos
- 50 ativos
- 90 ativos

Os portfólios foram rebalanceados com base na Fórmula Mágica e comparados ao desempenho do índice IBOV.

## 📈 Principais Resultados

- A carteira com **1 ativo** foi a mais rentável, com retorno acumulado de **5,05x** (aprox. **30% a.a.**).
- A versão com **5 ativos** também teve ótimo desempenho: **3,74x**.
- O **IBOVESPA**, usado como benchmark, entregou **1,59x** no mesmo período.

Apesar da ausência de métricas de risco, o padrão é claro: quanto menor a diversificação, maior o potencial de retorno — e maior o desvio em relação à média de mercado.

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas
- Matplotlib
- yFinance / dados fundamentalistas locais (caso aplicável)
- Jupyter Notebook
