## Qué copiar (Priorización)

- **Datos más críticos**
  - Bases de datos de Contabilidad y Clientes (20 GB)

- **Alta prioridad**
  - Documentos de Proyectos (300 GB)

- **Prioridad media**
  - Carpetas personales de los usuarios (100 GB)

- **Equipos clientes**
  - Copiar únicamente la carpeta **Documentos**

 
## Periodicidad y tipo de copia

| **Tipo de datos**                | **Copia diaria**                       | **Copia semanal**              | **Copia mensual** |
| -------------------------------- | -------------------------------------- | ------------------------------ | ----------------- |
| **Bases de datos**               | Incremental cada 4 h + Completa diaria | Completa                       | Completa          |
| **Proyectos**                    | Incremental                            | Completa                       | Completa          |
| **Carpetas personales**          | Incremental                            | Completa                       | Completa          |
| **Equipos Windows (Documentos)** | Incremental                            | Completa (semanal o quincenal) | Completa          |

## Medios y Ubicación (Regla 3-2-1)

- **Medio principal**
  - NAS interno (copias diarias)

- **Medio secundario**
  - Disco duro externo (copia semanal, desconectado)

- **Medio off-site**
  - Copia en la nube (Cloud, mensual)

## Regla 3-2-1
- **3** copias (servidor + NAS + Cloud)
- **2** tipos de medios (NAS + HDD/Cloud)
- **1** copia fuera del edificio (Cloud)
