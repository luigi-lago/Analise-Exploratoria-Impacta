# Análise Exploratória — Atrasos em Companhias Aéreas

> **Projeto original:** Pós-graduação em MBA Data Science & Advanced Analytics — Faculdade Impacta (Set/2024)
> **Evolução pessoal:** Estudos e experimentos com novas bibliotecas e técnicas (2026)

---

## 📌 Linha do tempo

### v1.0-impacta (tag) — Trabalho Original
- Notebook original em `Notebooks/analise_exploratoria.ipynb`
- Análise com pandas + matplotlib
- Dataset: NYC Flights 2013 via URL remota
- PDF com apresentação final

**Branch:** `main` (protegida, intacta)

### Evolução pessoal (branch `evolucao-polars`)
Objetivo: reanalisar o mesmo dataset com ferramentas modernas e técnicas estatísticas mais robustas.

- **polars** → processamento mais rápido e eficiente em memória
- **plotly** → gráficos interativos
- **scipy/statsmodels** → testes de hipótese formais (ANOVA, Kruskal-Wallis, correlação)
- Estrutura CRISP-DM com dados locais versionados

**Branch:** `evolucao-polars`

---

## 🗺️ O que vem por aqui

| Etapa | Foco | Status |
|-------|------|--------|
| Semana 1 | Polars + EDA + testes estatísticos | 🔜 Em breve |
| Semana 2 | Modelagem preditiva (XGBoost + Optuna) | ⏳ Planejado |
| Demais | Ver roadmap em `roadmap_ds_ia.md` | ⏳ Planejado |

---

## 🧪 Ambiente

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install polars plotly scipy statsmodels nbformat ipykernel
```

Dados: `data/raw/nycflights.csv` (baixado localmente via curl)
Dataset original: https://raw.githubusercontent.com/JackyP/testing/master/datasets/nycflights.csv
