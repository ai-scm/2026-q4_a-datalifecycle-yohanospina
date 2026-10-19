# 06. Etapa 5 – Archivado de Datos, Seguridad, Privacidad y Cumplimiento

Este documento aborda la quinta y última etapa del ciclo de vida de los datos (**archivado y retención**), junto con los tres pilares transversales fundamentales para cualquier arquitectura analítica en la nube: **seguridad, privacidad y cumplimiento regulatorio**.

---

## Mapa Mental

```mermaid
mindmap
  root((Archivado y Seguridad de Datos))
    Etapa 5 Archivado de Datos
      Retención a Largo Plazo
        Requisitos legales y auditoría
        Optimización continua de costos
      Amazon S3 Storage Classes
        S3 Glacier Instant Retrieval
        S3 Glacier Flexible Retrieval
        S3 Glacier Deep Archive
      S3 Lifecycle Policies
        Transición automática entre capas
        Expiración y eliminación segura
    Seguridad de Datos
      Control de Acceso AWS IAM
        Políticas JSON e identidades
        Principio de mínimo privilegio
      Cifrado de Datos
        En Tránsito TLS 1.3
        En Reposo AWS KMS
    Privacidad y Cumplimiento
      Cumplimiento Normativo
        GDPR HIPAA SOC PCI DSS
      Auditoría y Monitoreo
        AWS CloudTrail Registro de APIs
        Amazon Macie Identificación de PII
