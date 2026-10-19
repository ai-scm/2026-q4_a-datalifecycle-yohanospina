# 03. Etapa 2 – Montaje de Datos (Staging y Almacenamiento)

Este documento profundiza en la segunda etapa del ciclo de vida de los datos: el **montaje y almacenamiento** (*staging & storage*). Se explora la arquitectura de **Data Lake** sobre Amazon S3, la gobernanza centralizada con AWS Lake Formation y la estrategia de **bases de datos con propósito específico** (*Purpose-Built Databases*) que abarca entornos OLTP, NoSQL, In-Memory y OLAP (Data Warehouse).

---

## Mapa Mental

```mermaid
mindmap
  root((Etapa 2: Montaje de Datos))
    Arquitectura de Data Lake
      Amazon S3
        Almacenamiento de objetos masivo
        Desacoplamiento de cómputo y almacenamiento
        Capas Bronze Silver y Gold
      AWS Lake Formation
        Gobernanza y seguridad centralizada
        Control de acceso a nivel de fila y columna
    Bases de Datos Relacionales OLTP
      Amazon RDS
        MySQL PostgreSQL Oracle SQL Server
      Amazon Aurora
        Rendimiento empresarial y Serverless v2
    Bases de Datos NoSQL y Documentos
      Amazon DynamoDB
        Clave-valor con latencia de milisegundo de un solo dígito
      Amazon DocumentDB
        Compatible con MongoDB
    Almacenamiento en Memoria
      Amazon ElastiCache
        Caching distribuido con Redis y Memcached
    Data Warehouse OLAP
      Amazon Redshift
        Análisis analítico masivo en Petabytes
        Redshift Serverless y arquitectura RA3
