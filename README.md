# GenerativeRiskSim
https://website-builder--fabriciocabrera.replit.app/
**Sistema de IA generativa que simula escenarios financieros extremos y genera políticas de decisión óptimas para la gestión de riesgo en entornos financieros complejos.**

---

## Descripción del proyecto
GenerativeRiskSim es un framework de IA generativa diseñado para simular escenarios financieros extremos y generar estrategias de decisión adaptativas para la gestión de riesgo institucional. En lugar de predecir precios directamente, el sistema genera múltiples futuros plausibles del mercado y evalúa políticas bajo condiciones de alta incertidumbre.

El objetivo es proporcionar a las instituciones financieras una herramienta para evaluar riesgos sistémicos, shocks exógenos y eventos raros que no pueden capturar los modelos estadísticos tradicionales.

---

## Funcionalidades principales
- Generación de escenarios financieros sintéticos realistas, incluyendo eventos extremos.
- Evaluación de políticas de decisión adaptativas para manejo de riesgo.
- Comparación con modelos clásicos como ARIMA y LSTM.
- Métricas de robustez: drawdown, volatilidad y estabilidad de estrategias.
- Capacidad de integración con datos históricos y noticias financieras.

---

## Tecnologías y librerías
- **Lenguaje:** Python
- **Modelos generativos:** Transformers, Diffusion Models, VAE
- **Librerías:** PyTorch, TensorFlow, Hugging Face Transformers, pandas, numpy, scikit-learn, matplotlib, seaborn
- **Entornos:** Jupyter Notebook, Google Colab (para entrenamiento con GPU)

---

## Datos utilizados
- Series temporales financieras públicas (Yahoo Finance, Quandl, FRED)
- Eventos externos y noticias económicas relevantes
- Datos sintéticos generados por modelos generativos para simular escenarios raros o extremos

---

## Metodología
1. **Preparación de datos:** limpieza y normalización de series temporales y eventos.
2. **Entrenamiento del modelo generativo:** aprendizaje de la estructura del mercado y generación de múltiples futuros plausibles.
3. **Simulación multi-horizonte:** escenarios para diferentes plazos (1 semana, 1 mes, 3 meses).
4. **Módulo de decisión:** generación y evaluación de políticas adaptativas.
5. **Evaluación comparativa:** métricas de riesgo frente a modelos tradicionales.

---

## Cronograma propuesto

| Mes | Actividad |
|-----|-----------|
| 1   | Diseño, recolección de datos, baseline con modelos clásicos |
| 2   | Desarrollo del modelo generativo y experimentos iniciales |
| 3   | Simulaciones finales, evaluación de políticas y redacción del artículo IEEE |

---

## Resultado esperado
- Framework reproducible de simulación financiera basada en IA generativa.
- Evaluación comparativa con modelos predictivos clásicos.
- Métricas de riesgo, estabilidad y robustez de políticas.
- Artículo científico listo para presentar en conferencias IEEE (IRAI 2026 o IECON 2026).

---

## Licencia
Este proyecto se distribuye bajo **MIT License**, permitiendo uso académico y colaboración abierta.
