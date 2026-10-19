# Guía del Ciclo de Vida de los Datos y Análisis en la Nube de AWS

Este repositorio contiene la documentación detallada y diagramas de arquitectura en **Markdown** (con sintaxis **Mermaid**) correspondientes a la *Guía de referencia del ciclo de vida de los datos de AWS*.

---

## Índice de Contenidos

| Módulo | Archivo | Cobertura y Servicios Clave |
| :--- | :--- | :--- |
| **01** | [`01_introduccion_y_desafios.md`](./01_introduccion_y_desafios.md) | Introducción, Desafíos de la Gestión de Datos (las 5 Vs) y Visión General del Ciclo de Vida. |
| **02** | [`02_etapa1_ingesta.md`](./02_etapa1_ingesta.md) | Ingesta de datos (Batch vs. Streaming) y servicios de transferencia (Kinesis, MSK, AppFlow, Direct Connect, DataSync). |
| **03** | [`03_etapa2_montaje.md`](./03_etapa2_montaje.md) | Montaje de datos, Data Lakes (S3) y almacenamiento persistente (DynamoDB, Aurora, Redshift, OpenSearch). |
| **04** | [`04_etapa3_limpieza.md`](./04_etapa3_limpieza.md) | Limpieza, transformación y flujos ETL (AWS Glue, EMR, AWS Glue DataBrew, Step Functions). |
| **05** | [`05_etapa4_analisis_y_visualizacion.md`](./05_etapa4_analisis_y_visualizacion.md) | Análisis de datos (Athena, Redshift Spectrum), IA/ML (SageMaker, Bedrock) y visualización (Amazon QuickSight). |
| **06** | [`06_etapa5_archivado_y_seguridad.md`](./06_etapa5_archivado_y_seguridad.md) | Archivado (S3 Glacier), Gobernanza (Lake Formation), Seguridad (KMS, IAM), Privacidad y Cumplimiento. |
