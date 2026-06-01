# Guion Pitch — MLOps y AIOps

## 1. Introducción: problema que resuelve

Hoy muchas organizaciones logran entrenar modelos de Machine Learning, pero el verdadero problema aparece después: llevarlos a producción y mantenerlos funcionando bien.

Aquí aparece MLOps, que significa Machine Learning Operations. Es una disciplina que combina Machine Learning, desarrollo de software y operaciones para gestionar todo el ciclo de vida de un modelo: desde los datos y el entrenamiento, hasta el despliegue, monitoreo y mejora continua.

Sin MLOps, los modelos pueden quedar como experimentos aislados: difíciles de repetir, difíciles de desplegar y difíciles de mantener.

Por eso, MLOps resuelve el problema de convertir un modelo experimental en un sistema real, confiable y operable en producción.

## 2. Contenido: qué hicimos

Para este ejercicio trabajé dos lecturas principales de ml-ops.org:

* **End-to-End ML Workflow Lifecycle**
* **MLOps Stack Canvas**

En la primera lectura revisé el ciclo completo de un sistema de Machine Learning.

Este ciclo se divide en tres grandes partes:

Primero, **Data Engineering**, donde se recolectan, limpian, validan y dividen los datos.

Luego, **Model Engineering**, donde se entrena el modelo, se ajustan hiperparámetros, se evalúa su rendimiento y se empaqueta la mejor versión.

Finalmente, **Model Deployment**, donde el modelo se integra a una aplicación real, se expone para hacer predicciones y se monitorea su comportamiento en producción.

La idea clave es que el modelo no termina cuando se entrena. En producción, los datos cambian; el rendimiento puede bajar y por eso se necesita monitoreo y reentrenamiento.

En la segunda lectura trabajé el **MLOps Stack Canvas**, que funciona como una vista general para diseñar la infraestructura de un sistema de Machine Learning.

Este Canvas ayuda a identificar componentes como fuentes de datos, versionado, experimentos, pipelines, registro de modelos, despliegue, monitoreo y metadatos.

También permite entender el nivel de madurez de una organización frente a la IA: desde una etapa táctica, con pruebas manuales, hasta una etapa transformacional, donde la IA ya está integrada al negocio y el ciclo está mucho más automatizado.

Además, conecté esto con el taller anterior de **MLflow**, porque MLflow encaja dentro del ecosistema MLOps al permitir registrar experimentos, comparar métricas, versionar modelos y apoyar su paso hacia producción.

## 3. Comparación con AIOps

Finalmente, también revisé la relación entre **MLOps** y **AIOps**.

**MLOps** se enfoca en operar modelos de Machine Learning: entrenarlos, versionarlos, desplegarlos, monitorearlos y mantenerlos actualizados.

**AIOps**, en cambio, significa **Artificial Intelligence for IT Operations**. Su objetivo es usar inteligencia artificial para mejorar la operación de sistemas tecnológicos, por ejemplo detectando fallos, analizando métricas, reduciendo alertas repetidas o automatizando respuestas ante incidentes.

La relación principal es que ambos trabajan con datos, automatización, monitoreo y mejora continua.

La diferencia es que **MLOps opera modelos de IA**, mientras que **AIOps usa IA para operar infraestructura y sistemas tecnológicos**.

## 4. Conclusión

Este ejercicio es importante porque muestra que Machine Learning no se trata solo de entrenar un modelo y obtener una buena métrica.

En un contexto real, un modelo debe poder mantenerse funcionando, adaptarse a nuevos datos, ser monitoreado, versionado y actualizado cuando sea necesario.

Por eso MLOps es clave: convierte modelos aislados en sistemas confiables que pueden generar valor real en producción.

