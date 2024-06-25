# Exploratory and Temporal Analysis of Oil Well Production in Argentina

This analysis explores data from 2020 on oil well production in Argentina. The data used can be found in this [Google Drive folder](https://drive.google.com/drive/folders/1lgD0gZq76QFelkK3sJDb-n46Ntgx532O?usp=sharing) as the original page from [datos.gob.ar](https://datos.gob.ar/dataset) is not always available.

In the exploratory analysis, I focus only on data from March 2024, while in the temporal analysis I use data from January 2020 to March 2024.
For the Spanish version of this document, please see [here](README.md).

## Exploratory Analysis

In this analysis, I familiarize myself with the dataset, removing irrelevant elements for the study's objective.

### Exploratory Analysis Questions

1. **How many wells are there per province?**
   
   ![pozos-provincia](img/exploratorio/estado_cantidad_prov.png)

2. **What is the percentage of non-abandoned wells per province?**

   ![porcentaje-pozos-no-abandonados-provincia](img/exploratorio/torta_porcentajes_prov.png)

3. **How many active wells are there per province?**

   ![pozos-activos-provincia](img/exploratorio/pozos_activos_prov.png)

4. **What is the production per province?**

   ![produccion-gas-pet-por-prov](img/exploratorio/prod_prov.png)

5. **Which company has the highest production?**

   ![produccion-por-empresa](img/exploratorio/prod_gas_pet_prov.png)

6. **Which basin produces the most?**

   ![produccion-por-cuenca](img/exploratorio/prod_gas_pet_cuenca.png)

7. **What is the most frequent type of extraction?**

   ![tipo-extraccion](img/exploratorio/tipo-extraccion.png)

---

## Temporal Analysis

### Temporal Analysis Questions

1. **What is the quarterly evolution?**

   ![trim_pet_gas](img/temporal/trimestral-pet-gas.png)
   ![trim_agua](img/temporal/trimestral-agua.png)

2. **What is the monthly evolution?**

   ![mens_pet_gas](img/temporal/mensual_pet_gas.png)
   ![mens_agua](img/temporal/mensual_agua.png)

3. **Production by the top 5 companies**

   **Production of Oil, Gas, and Water**
   ![top-empr-pet](img/temporal/top_empresas/top_empresas_prod_pet.png)
   ![top-empr-gas](img/temporal/top_empresas/top_empresas_prod_gas.png)
   ![top-empr-agua](img/temporal/top_empresas/top_empresas_prod_agua.png)

4. **Production by Basin**

   **Production of Oil, Gas, and Water**
   ![cuen-pet](img/temporal/cuencas/prod_pet_cuenca.png)
   ![cuen-gas](img/temporal/cuencas/prod_gas_cuenca.png)
   ![cuen_agua](img/temporal/cuencas/prod_agua_cuenca.png)

For the Spanish version of this document, please see [here](README.md).
