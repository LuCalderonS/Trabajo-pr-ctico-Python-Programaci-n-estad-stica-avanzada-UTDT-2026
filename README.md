# Trabajo-practico-Python-Programacion-estadistica-avanzada-UTDT-2026
El repositorio contiene el código desarrollado y las explicaciones correspondientes a las consignas dadas para el trabajo práctico de Python de la materia Programación Estadística Avanzada de la UTDT en el segundo trimestre de 2026
El trabajo se divide en tres partes independientes:

1. **Parte 1: Robustez ante contaminación de muestras**
   * **1.1 Estimadores de tendencia central:** Evaluación del sesgo y el Error Cuadrático Medio (ECM) de la media frente a la mediana bajo distintos niveles de contaminación con *outliers* a través de $M = 1000$ simulaciones.
   * **1.2 Regresión lineal bajo contaminación:** Implementación manual de OLS utilizando la fórmula matricial $\beta = (X^{\prime}X)^{-1}X^{\prime}y$ y del estimador LAD, evaluando su desempeño en $M = 500$ simulaciones.

2. **Parte 2: Paradoja de Simpson y variables omitidas**
   * Simulación de un modelo con variables discretas y continuas donde se evidencia cómo la omisión de variables de control distorsiona el efecto real de $X$ sobre $Y$. 
   * Análisis de la distribución del estimador $\beta_X$ bajo tres especificaciones (sin controles, con control $Z$ y con control $W$) y demostración empírica de que el sesgo por variable omitida no desaparece con muestras grandes, acompañado de su respectiva ilustración visual de la paradoja.

3. **Parte 3: Análisis empírico con Gapminder**
   * **Pregunta A (Convergencia):** Estimación y visualización de la brecha en esperanza de vida de un país seleccionado respecto al promedio mundial entre 1952 y 2007.
   * **Pregunta B (Atipicidad):** Identificación, cuantificación y explicación histórico-económica del período de mayor desviación de la trayectoria del país en relación con el promedio de su continente.

---

## Estructura

* **Notebook Ejecutable:** Todo el código se encuentra integrado en un notebook de Google Colab ejecutable de principio a fin, configurado con una semilla fija al inicio para garantizar la reproducibilidad.
* **Interpretación:** Cada parte incluye celdas de Markdown dedicadas exclusivamente a la interpretación económica y estadística de los resultados obtenidos.

---

## Cómo Ejecutar el Proyecto

1. Cloná este repositorio o descargá el archivo del notebook de Colab disponible en el repositorio.
2. Abrí el notebook directamente en **Google Colab** haciendo clic en el enlace provisto o subilo a tu entorno de Google Drive.
3. Ejecutá las celdas en orden secuencial. El notebook descargará automáticamente las galerías y las fuentes de datos necesarias (como el dataset de Gapminder) y se ejecutará sin requerir modificaciones adicionales.
