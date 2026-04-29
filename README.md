# 📊 Optimización de Cartera de Inversión

Análisis y optimización de carteras de inversión utilizando la **Teoría Moderna de Portafolios (Markowitz)**, con comparación contra los principales índices bursátiles (S&P 500, Nasdaq 100, Dow Jones, Russell 2000).

Implementado en **Python** sobre **Google Colab**, usando datos en tiempo real de Yahoo Finance.

---

## 🎯 Características

- 📈 Descarga automática de datos históricos vía `yfinance`
- 🧮 Optimización de cartera por **máximo Sharpe Ratio**
- 🛡️ Cálculo de cartera de **mínima volatilidad**
- 🎲 Simulación **Monte Carlo** con 10.000 portafolios aleatorios
- 📉 Visualización de la **frontera eficiente**
- 📊 Comparación contra índices: S&P 500, Nasdaq 100, Dow Jones, Russell 2000
- 📐 Métricas de riesgo: **Drawdown**, **Beta**, **Correlación**, **Sharpe Ratio**
- 💾 Exportación de resultados a **Excel** (multi-hoja) y gráficos en **PNG**

---

## 🛠️ Tecnologías

- **Python 3.x**
- **NumPy** – Cálculo numérico
- **Pandas** – Manipulación de datos
- **yfinance** – Datos de mercado
- **SciPy** – Optimización (SLSQP)
- **Matplotlib** – Visualización
- **OpenPyXL** – Exportación a Excel
- **Google Colab** – Entorno de ejecución

---

## 🚀 Instalación

### Opción 1: Google Colab (recomendado)

1. Abrí [Google Colab](https://colab.research.google.com/)
2. Creá un nuevo notebook
3. Pegá los bloques de código en celdas separadas
4. Ejecutá en orden

### Opción 2: Local

```bash
