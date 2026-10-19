# 02. Etapa 1 – Ingesta de Datos

Este documento aborda en profundidad la primera etapa del ciclo de vida de los datos: la **ingesta**. Se detallan los patrones de ingesta (por lotes y en tiempo real), las diferencias entre servicios de procesamiento de eventos en *streaming* y las herramientas de migración masiva e híbrida dentro del ecosistema de AWS.

---

## Mapa Mental (Mermaid)

```mermaid
mindmap
  root((Etapa 1: Ingesta de Datos))
    Patrones de Ingesta
      Por Lotes Batch
        Procesamiento periódico
        Volúmenes masivos discretos
      En Tiempo Real Streaming
        Flujo continuo de eventos
        Baja latencia y reacción inmediata
    Servicios de Streaming
      Amazon Kinesis
        Kinesis Data Streams
        Kinesis Data Firehose
      Amazon MSK
        Managed Apache Kafka
    Servicios de Migración de Red
      AWS DataSync
        Transferencia de archivos local-nube
      AWS DMS
        Migración de bases de datos
      AWS Storage Gateway
        Conexión híbrida de almacenamiento
    Migración Física Masiva
      Familia AWS Snow
        AWS Snowcone: Portátil de 8 TB
        AWS Snowball: Petabytes
        AWS Snowmobile: Exabytes
