# Manuel Alejandro Del Rosal — Portafolio

> Physicist & M.S. Candidate in Applied Mathematics & CS. Data Science · Quantitative Finance · Computational Physics · Health Analytics. 🔭💻

Este repo es el **hub** de mi portafolio: cada área vive en su propio repositorio independiente, conectado aquí como [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules). La idea es doble — mostrar el trabajo en cada área con su propio historial, versiones y flujo de PRs, y que el propio hub sea una muestra de manejo de git más allá de lo básico.

## 🌳 Árbol del portafolio

```
Portafolio (este repo — hub)
│
├── 🧪 physics-computational      Mecánica cuántica, caos, Monte Carlo, dinámica molecular
├── 💹 quant-finance-lab          VaR/CVaR, pricing de derivados, backtesting, NLP financiero
├── 🤖 ml-portfolio                Credit risk scoring y más modelos de ML (creciendo todo el año)
├── 🛠️ data-engineering-dbt        Pipelines ELT con dbt — en construcción
├── ☁️ mlops-aws                   Despliegue de ML en AWS (SageMaker, Lambda, IaC) — en construcción
├── 🩺 medical-health-analytics    Costos de salud, riesgo clínico, epidemiología
└── 🧬 bio-humanity-research       Investigación personal: biología computacional + cliodinámica
```

| Área | Repo | Estado |
|---|---|---|
| Física computacional | [physics-computational](https://github.com/AlejandroDelRosal/physics-computational) | ![CI](https://img.shields.io/github/actions/workflow/status/AlejandroDelRosal/physics-computational/ci.yml?branch=main&label=CI) |
| Finanzas cuantitativas | [quant-finance-lab](https://github.com/AlejandroDelRosal/quant-finance-lab) | ![CI](https://img.shields.io/github/actions/workflow/status/AlejandroDelRosal/quant-finance-lab/ci.yml?branch=main&label=CI) |
| Machine Learning | [ml-portfolio](https://github.com/AlejandroDelRosal/ml-portfolio) | ![CI](https://img.shields.io/github/actions/workflow/status/AlejandroDelRosal/ml-portfolio/ci.yml?branch=main&label=CI) |
| Data engineering (dbt) | [data-engineering-dbt](https://github.com/AlejandroDelRosal/data-engineering-dbt) | 🚧 en construcción |
| MLOps / AWS | [mlops-aws](https://github.com/AlejandroDelRosal/mlops-aws) | 🚧 en construcción |
| Salud / medicina | [medical-health-analytics](https://github.com/AlejandroDelRosal/medical-health-analytics) | ![CI](https://img.shields.io/github/actions/workflow/status/AlejandroDelRosal/medical-health-analytics/ci.yml?branch=main&label=CI) |
| Biología & humanidad | [bio-humanity-research](https://github.com/AlejandroDelRosal/bio-humanity-research) | 🚧 investigación abierta |

## Cómo está organizado (para quien clone esto)

```bash
git clone --recurse-submodules https://github.com/AlejandroDelRosal/Portafolio.git
# o si ya lo clonaste sin submodules:
git submodule update --init --recursive
```

Cada área es un repo con su propio `main` protegido, conventional commits, releases semánticos (`v0.1.0`, `v0.2.0`...) y CI. El hub solo fija *qué versión* de cada área está enlazada — actualizar un submodule a un commit más nuevo es en sí mismo un PR normal (`chore: bump physics-computational to vX.Y`).

## Sobre mí

Físico en transición hacia ciencia de datos y finanzas cuantitativas, cursando una maestría con enfoque en métodos numéricos avanzados y programación científica/HPC. Este portafolio es un proyecto vivo — se actualiza a lo largo del año, área por área.

## 📫 Contacto

* [LinkedIn](https://www.linkedin.com/in/alejandro-delrosal-saucedo/)
* mars.delrosal@gmail.com
