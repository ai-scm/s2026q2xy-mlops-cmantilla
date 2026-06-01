# Guion Pitch — MLOps y AIOps

## 1. Introducción: problema que resuelve

Hoy muchas organizaciones logran entrenar modelos de Machine Learning, pero el verdadero problema aparece después: llevarlos a producción y mantenerlos funcionando bien.

Un modelo no vive solo en un notebook. Necesita datos confiables, código versionado, despliegue, monitoreo, métricas, alertas y actualización constante.

Sin MLOps, los modelos pueden quedar como experimentos aislados: difíciles de repetir, difíciles de desplegar y difíciles de mantener.

Por eso, MLOps aparece como una forma de organizar todo el ciclo de vida de Machine Learning, conectando datos, modelos, software y operación.

## 2. Contenido: qué hicimos

Para este ejercicio trabajé dos lecturas principales de ml-ops.org:

* **End-to-End ML Workflow Lifecycle**
* **MLOps Stack Canvas**

En la primera lectura revisé el ciclo completo de un sistema de Machine Learning.

Este ciclo se divide en tres grandes partes:

Primero, **Data Engineering**, donde se recolectan, limpian, validan y dividen los datos.

Luego, **Model Engineering**, donde se entrena el modelo, se ajustan hiperparámetros, se evalúa su rendimiento y se empaqueta la mejor versión.

Finalmente, **Model Deployment**, donde el modelo se integra a una aplicación real, se expone para hacer predicciones y se monitorea su comportamiento en producción.

La idea clave es que el modelo no termina cuando se entrena. En producción, los datos cambian, el rendimiento puede bajar y por eso se necesita monitoreo y reentrenamiento.

En la segunda lectura trabajé el **MLOps Stack Canvas**, que funciona como una vista general para diseñar la infraestructura de un sistema de Machine Learning.

Este Canvas ayuda a identificar componentes como fuentes de datos, versionado, experimentos, pipelines, registro de modelos, despliegue, monitoreo y metadatos.

También permite entender el nivel de madurez de una organización frente a IA: desde una etapa táctica, con pruebas manuales, hasta una etapa transformacional, donde la IA ya está integrada al negocio y el ciclo está mucho más automatizado.

Además, conecté esto con el taller anterior de **MLflow**, porque MLflow encaja dentro del ecosistema MLOps al permitir registrar experimentos, comparar métricas, versionar modelos y apoyar su paso hacia producción.

## 3. Conclusión

En conclusión, MLOps resuelve el problema de pasar de “tengo un modelo que funciona en mi computador” a “tengo un sistema de Machine Learning confiable, monitoreado y mantenible en producción”.

También encontré una relación directa con **AIOps**.

Mientras MLOps se encarga de operar modelos de Machine Learning, AIOps usa inteligencia artificial para mejorar la operación de sistemas tecnológicos, por ejemplo detectando fallos, analizando métricas o automatizando respuestas.

Ambos comparten la misma lógica: usar datos, automatización y monitoreo continuo para que los sistemas sean más confiables.

Por eso, MLOps ayuda a construir y mantener modelos de IA, y AIOps usa esos modelos para mejorar la operación tecnológica.
