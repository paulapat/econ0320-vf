# PIB, tendencia e inflación

Material didáctico de **Econometría I** (Universidad de Montevideo).
Análisis de la serie de PIB de Uruguay: visualización, estimación de
tendencias y descomposición en componente tendencial y cíclico-irregular.

## Estructura

```
econometria-pib/
├── analisis_pib.qmd     # documento Quarto principal
├── data/
│   └── series.xlsx      # datos
├── README.md
└── .gitignore
```

## Requisitos

- R (>= 4.1) — usa el operador nativo `|>`
- [Quarto](https://quarto.org/docs/get-started/)
- Paquetes: `readxl`, `dplyr`, `ggplot2`, `here`

```r
install.packages(c("readxl", "dplyr", "ggplot2", "here"))
```

## Cómo correr

1. Cloná el repo:
   ```bash
   git clone https://github.com/tu-usuario/econometria-pib.git
   cd econometria-pib
   ```
2. Abrí `analisis_pib.qmd` en RStudio y apretá **Render**.
   O desde la terminal:
   ```bash
   quarto render analisis_pib.qmd
   ```
3. Se genera `analisis_pib.html` con todo el análisis.
