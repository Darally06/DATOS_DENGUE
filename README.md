# 🦟 **Datos de Dengue – SIVIGILA (Colombia, Atlántico y Barranquilla)**

Este repositorio contiene los **conjuntos de datos consolidados del sistema SIVIGILA**, correspondientes a los casos de **dengue clásico y dengue grave** registrados en **Colombia**, el **departamento del Atlántico** y el **municipio de Barranquilla**.

Los archivos aquí disponibles han sido estructurados y estandarizados para su uso en análisis exploratorios.

> ⚠️ El proceso de extracción y limpieza de estos datos se encuentra documentado en el repositorio complementario:
> 👉 [ETL_DENGUE](https://github.com/Darally06/ETL_DENGUE)


## 📂 **Estructura del Repositorio**

* `Data_Colombia.csv/` → Casos de dengue registrados en Colombia (2013–2023).
* `Data_Atlantico.csv/` → Casos de dengue registrados en el Atlántico (2017–2023).
* `Data_Barranquilla.csv/` → Casos de dengue registrados en Barranquilla (2017–2023).

## 🧾 **Fuente de Datos**

| **Fuente**   | **Unidad geográfica** | **Periodo** | **Descripción**                                         |
| ------------ | --------------------- | ----------- | ------------------------------------------------------- |
| **SIVIGILA** | Colombia              | 2013–2023   | Registro nacional de casos de dengue (clásico y grave). |
| **SIVIGILA** | Atlántico             | 2017–2023   | Registro departamental de casos.                        |
| **SIVIGILA** | Barranquilla          | 2017–2023   | Registro municipal de casos.                            |


## 📊 **Descripción de Variables Principales**

| **Categoría**    | **Variables**                                                                   |
| ---------------- | ------------------------------------------------------------------------------- |
| **Demográficas** | Edad (años), ciclo vital, sexo, grupo étnico, régimen de salud.                 |
| **Espaciales**   | Departamento, municipio, área, localidad (Barranquilla).                        |
| **Temporales**   | Año, semana epidemiológica, fecha de inicio de síntomas, fecha de consulta.     |
| **Evento**       | Tipo de evento (dengue clásico o grave), tipo de caso, hospitalización, muerte. |


## 🗺️ **Cobertura Geográfica y Temporal**

* **Cobertura:** Nacional, departamental y municipal (Colombia, Atlántico, Barranquilla).
* **Periodo de análisis:**

  * Colombia: **2013–2023**
  * Atlántico: **2017–2023**
  * Barranquilla: **2017–2023**

## 🔗 **Repositorio Relacionado**

* 🧮 **ETL y procesamiento de datos:** [ETL_DENGUE](https://github.com/Darally06/ETL_DENGUE)
* 📊 **Análisis Exploratorio de Datos:** [EDAs](https://github.com/Darally06/Dengue_caracterization) 

