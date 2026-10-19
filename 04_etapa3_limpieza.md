# 04. Etapa 3 – Limpieza y Transformación de Datos (ETL/ELT)

Este documento analiza la tercera etapa del ciclo de vida de los datos: **limpieza y transformación**. Se exploran los paradigmas de procesamiento (ETL vs. ELT), los servicios serverless y de Big Data masivo de AWS para el modelado de datos (AWS Glue, Amazon EMR) y las herramientas de orquestación de flujos de trabajo (*pipelines*).

---

## Mapa Mental

```mermaid
mindmap
  root((Etapa 3: Limpieza y Transformación))
    Paradigmas
      ETL Extract Transform Load
      ELT Extract Load Transform
    AWS Glue Ecosystem
      Serverless ETL Engine
        Jobs en PySpark y Python
      AWS Glue Data Catalog
        Metastore centralizado
      AWS Glue DataBrew
        Preparación visual sin código
    Big Data a Escala Masiva
      Amazon EMR
        Apache Spark Hadoop Hive Presto
        EMR Serverless y EMR on EKS
    Orquestación de Pipelines
      AWS Step Functions
        Flujos visuales basados en eventos
      Amazon MWAA
        Apache Airflow gestionado en Python
