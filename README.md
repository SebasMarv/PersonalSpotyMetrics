# PersonalSpotyMetrics

### Fase 1 - Análisis Historico
La fase 1 constara de obtener data historica de registros musicales de spotify respecto a mi cuenta personal para poder analizarlos y visualizar las metricas de mi trayectoria en spotify como oyente.

**Herramientas a utilizar:**
* BD | DATABRICKS | API | GIT | APACHE SUPERSET
* DATALAKE | DOCKER | SCIKITLEARN

**Preparativos:**
* Crear repositorio en github. ☑️
    - [PersonalSpotyMetrics]
* Crear notebook en databricks community. ☑️
    - Directorio: PersonalSpotyMetrics
        - 1.Creación de Modelo Medallon e Ingesta (Temp -> Bronze)
        - 2.Pipeline de Depuración (Bronze -> Silver)
        - 3.Transformación y Enriquecimiento (Silver -> Gold)
* Montar datalake en databricks. ☑️
    - Montado sin visualizar por credenciales.
        - /mnt/dlake/
* Emplear arquitectura medallon en el proyecto. ☑️
    - 1.Creación de Modelo Medallon e Ingesta (Temp -> Bronze)
        - Directorio: /amarquez/PersonalSpotyMetrics/data/
            - temp
            - bronze
            - silver
            - golden
* Mapeo de endpoints a utilizar.
* Creación de una base de datos nube.
* Levantar apache superset.

**Procesamiento:**
* Ingesta y depuración de historial musical del usuario. 
* Ingesta mediante endpoints de características de cada
registro musical. 
* Preparación y Transformación de datos enriquecidos.
* Aplicar modelos de clasificación.
* Analisis descriptivo del dataset.
* Visualización del analisis en superset.

