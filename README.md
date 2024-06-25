# Análisis Exploratorio y Temporal de la Producción de Pozos Petroleros en Argentina

Este análisis explora los datos desde el 2020 de la producción de pozos petroleros en Argentina. Los datos utilizados se encuentran en esta [carpeta de Google Drive](https://drive.google.com/drive/folders/1lgD0gZq76QFelkK3sJDb-n46Ntgx532O?usp=sharing) ya que la página original de [datos.gob.ar](https://datos.gob.ar/dataset) no siempre está disponible.

En el análisis exploratorio, me enfoco solo en los datos de marzo de 2024, mientras que en el análisis temporal uso datos desde enero de 2020 a marzo de 2024.
Para la versión en inglés de este documento, consulte [aquí](README_en.md).

## Análisis Exploratorio

En este análisis, me familiarizo con el dataset, eliminando elementos irrelevantes para el objetivo del estudio.

### Preguntas del Análisis Exploratorio

1. **¿Cuántos pozos hay por provincia?**
   
   ![pozos-provincia](img/exploratorio/estado_cantidad_prov.png)

2. **¿Cuál es el porcentaje de pozos no abandonados por provincia?**

   ![porcentaje-pozos-no-abandonados-provincia](img/exploratorio/torta_porcentajes_prov.png)

3. **¿Cuántos pozos activos hay por provincia?**

   ![pozos-activos-provincia](img/exploratorio/pozos_activos_prov.png)

4. **¿Cuál es la producción por provincia?**

   ![produccion-gas-pet-por-prov](img/exploratorio/prod_prov.png)

5. **¿Qué empresa tiene la mayor producción?**

   ![produccion-por-empresa](img/exploratorio/prod_gas_pet_prov.png)

6. **¿Qué cuenca produce más?**

   ![produccion-por-cuenca](img/exploratorio/prod_gas_pet_cuenca.png)

7. **¿Cuál es el tipo de extracción más frecuente?**

   ![tipo-extraccion](img/exploratorio/tipo-extraccion.png)

---

## Análisis Temporal

### Preguntas del Análisis Temporal

1. **¿Cómo es la evolución trimestral?**

   ![trim_pet_gas](img/temporal/trimestral-pet-gas.png)
   ![trim_agua](img/temporal/trimestral-agua.png)

2. **¿Cómo es la evolución mensual?**

   ![mens_pet_gas](img/temporal/mensual_pet_gas.png)
   ![mens_agua](img/temporal/mensual_agua.png)

3. **Producción por las top 5 empresas**

   **Producción de Petróleo, Gas y Agua**
   ![top-empr-pet](img/temporal/top_empresas/top_empresas_prod_pet.png)
   ![top-empr-gas](img/temporal/top_empresas/top_empresas_prod_gas.png)
   ![top-empr-agua](img/temporal/top_empresas/top_empresas_prod_agua.png)

4. **Producción por Cuenca**

   **Producción de Petróleo, Gas y Agua**
   ![cuen-pet](img/temporal/cuencas/prod_pet_cuenca.png)
   ![cuen-gas](img/temporal/cuencas/prod_gas_cuenca.png)
   ![cuen_agua](img/temporal/cuencas/prod_agua_cuenca.png)

Para la versión en inglés de este documento, consulte [aquí](README_en.md).
