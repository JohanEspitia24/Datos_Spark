# Taller de SQL con **PySpark** 📊🔥  
Procesamiento de Alto Volumen de Datos

> **Notebook principal:** `Espitia_Cobos_SQL_Spark.ipynb`  
> **Autor:** **Johan Alejandro Espitia Cobos** – Pontificia Universidad Javeriana

---

## 📌 Descripción

Este proyecto muestra, paso a paso, cómo utilizar **Apache Spark** (vía PySpark) para ejecutar consultas SQL sobre datos estructurados de forma eficiente y escalable.  
Dentro del cuaderno se construyen pequeños _datasets_, se transforman en **DataFrames**, se crean vistas temporales y tablas administradas (Hive), y se ilustran operaciones fundamentales de **Spark SQL**:

1. Inicializar la **SparkSession**.  
2. Crear y transformar **DataFrames**.  
3. Clasificar registros con columnas calculadas (`when`, `otherwise`).  
4. Registrar **vistas temporales** y disparar consultas con `spark.sql()`.  
5. Persistir resultados como **tablas** con `write.saveAsTable()`.  
6. Insertar, consultar y filtrar datos directamente desde SQL.  
7. _(Sección futura)_ Introducción a **RDD API**.  
8. Conclusiones y reflexiones sobre el desempeño de Spark.

El notebook sirve como material didáctico para la asignatura **Procesamiento de Datos a Gran Escala** y como punto de partida para desarrollos más avanzados sobre Spark.

---

## 🏗️ Estructura del repositorio


---

## ⚙️ Requisitos

| Componente    | Versión recomendada |
|---------------|---------------------|
| Python        | 3.9 o superior      |
| Apache Spark  | 3.4.x / 3.5.x       |
| PySpark       | igual a la versión de Spark |
| JupyterLab    | 4.x                 |

> 💡 **Alternativa rápida:** usar la imagen Docker oficial `jupyter/pyspark-notebook`.

---

## 🚀 Puesta en marcha local

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/<TU_USUARIO>/<TU_REPOSITORIO>.git
   cd <TU_REPOSITORIO>
