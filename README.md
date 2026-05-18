# Modelo Oculto de Markov (HMM) para Regímenes de Mercado Financiero

## Descripción del proyecto

Este proyecto implementa un Modelo Oculto de Markkov (HMM) aplicado al análisis de mercados financieros con el objetivo de identificar regímenes de mercado a partir de los retornos observados.

Los regímenes de mercado representan estados ocultos que no pueden observarse directamente, pero que influyen en el comportamiento de los precios. En este caso se modelan tres estados principales:

* Mercado Alcista
* Mercado Lateral
* Mercado Bajista

A partir de estos estados se generan observaciones visibles clasificadas como:

* Retorno Positivo
* Retorno Neutral
* Retorno Negativo

Además, se utiliza simulación Monte Carlo para ejecutar múltiples escenarios de mercado, permitiendo calcular métricas financieras, análisis de riesgo y recomendaciones de trading.

---

## Objetivo

Simular un Modelo Oculto de Markov (HMM) que permita identificar regímenes de mercado financiero basándose en retornos observados, analizar el comportamiento de los precios y evaluar el riesgo mediante simulaciones Monte Carlo.

---

## Tecnologías utilizadas

* Python
* NumPy
* Matplotlib
* Pandas
* SciPy
* Google Colab

---

## Funcionalidades principales

* Implementación completa de un HMM para mercados financieros
* Simulación de 50 períodos de trading
* Generación de precios simulados
* Visualización gráfica del comportamiento del mercado
* Identificación de cambios de régimen
* Algoritmo de Viterbi para decodificación de estados ocultos
* Cálculo de métricas financieras:

  * Retorno total acumulado
  * Volatilidad
  * Drawdown máximo
  * Ratio de Sharpe
  * Value at Risk (VaR)
  * Conditional Value at Risk (CVaR)
* Recomendaciones automáticas de trading
* Análisis de riesgo financiero

---

## Cómo ejecutar el proyecto

### Opción recomendada: Google Colab

1. Abrir Google Colab
2. Crear un nuevo cuaderno
3. Copiar y pegar el código Python completo
4. Ejecutar todas las celdas
5. Revisar los resultados en consola y las gráficas generadas

---

## Resultados esperados

Al ejecutar el proyecto se obtienen:

* Simulación de trayectorias de precios
* Identificación de regímenes de mercado
* Análisis visual de cambios de régimen
* Evaluación de convergencia Monte Carlo
* Distribución de métricas financieras
* Recomendaciones de inversión según el estado actual del mercado

---

## Estructura del proyecto

* Código principal en Python
* Documento de sustentación (Word)
* Evidencias gráficas de resultados
* README del proyecto
* Repositorio organizado para entrega académica

---

## Autor

Lizeth Carolina Zuleta Herrera

Universidad Digital de Antioquia

---

## Observación final

Este proyecto tiene fines académicos y busca demostrar la aplicación de los Modelos Ocultos de Markov en el análisis financiero, integrando simulación, probabilidad, estadística y toma de decisiones bajo incertidumbre.
