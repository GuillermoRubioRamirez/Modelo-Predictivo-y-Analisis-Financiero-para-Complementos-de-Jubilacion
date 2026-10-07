## Sistema de cálculo de primas de jubilación personalizado y sostenible

Proyecto desarrollado en colaboración con Lagun Aro para la empresa Empaquetados Iberia S.A., con el objetivo de ofrecer un sistema de cálculo de primas de jubilación personalizado y sostenible para sus empleados.

Se diseñó un modelo predictivo de edad de jubilación utilizando técnicas de regresión lineal y Random Forest, considerando variables como edad, antigüedad, sueldo y sexo. Tras evaluar distintos enfoques de machine learning, se optó finalmente por una solución basada en la media, por su mayor robustez y precisión en contextos reales.

El análisis financiero incluyó proyecciones de inflación y rendimiento del capital, junto con un estudio de sensibilidad exhaustivo ante variaciones en la edad de jubilación, la inflación y el rendimiento esperado. A partir de este análisis se desarrollaron tres modelos de prima: pago mensual, prima única en 2024 y prima única al momento de la jubilación.

Como resultado final, se desarrolló una aplicación web en Flask que permite simular el coste de las primas bajo cada modalidad, democratizando el acceso a simulaciones financieras personalizadas para los empleados.
