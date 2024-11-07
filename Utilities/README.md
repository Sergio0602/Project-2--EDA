# Project-2--EDA

# Documentación de Variables de Emisiones de CO₂

### Información General
- **`country`**: Nombre del país al que corresponden los datos.
- **`year`**: Año en el que se recopilaron los datos.
- **`iso_code`**: Código ISO de tres letras para identificar el país (ej. `AFG` para Afganistán).
- **`population`**: Población total del país en el año dado.

### Emisiones de CO₂ por Sectores

- **`cement_co2`**: Emisiones de dióxido de carbono (CO₂) generadas por la industria del cemento, en millones de toneladas.
- **`cement_co2_per_capita`**: Emisiones de CO₂ de la industria del cemento divididas por la población del país (toneladas de CO₂ por persona).

### Emisiones Totales de CO₂

- **`co2`**: Emisiones totales de CO₂ del país en el año específico, en millones de toneladas.
- **`co2_growth_abs`**: Crecimiento absoluto en emisiones de CO₂ respecto al año anterior (en millones de toneladas).
- **`co2_growth_prct`**: Crecimiento porcentual en las emisiones de CO₂ respecto al año anterior.
- **`co2_including_luc`**: Emisiones de CO₂ totales, incluyendo el cambio de uso de la tierra (Land Use Change o LUC), en millones de toneladas.
- **`co2_including_luc_growth_abs`**: Crecimiento absoluto de las emisiones de CO₂ (incluyendo LUC) respecto al año anterior.
- **`co2_including_luc_growth_prct`**: Crecimiento porcentual de las emisiones de CO₂ (incluyendo LUC) respecto al año anterior.
- **`co2_including_luc_per_capita`**: Emisiones de CO₂ (incluyendo LUC) por persona en el país (toneladas de CO₂ por persona).
- **`co2_including_luc_per_gdp`**: Emisiones de CO₂ (incluyendo LUC) por unidad de PIB del país (eficiencia de carbono de la economía).

### Indicadores de Emisiones por Persona y por PIB

- **`co2_per_capita`**: Emisiones de CO₂ por persona en el país (toneladas de CO₂ por persona).
- **`co2_per_gdp`**: Emisiones de CO₂ por unidad de PIB (toneladas de CO₂ por dólar del PIB).

### Emisiones de CO₂ por Fuente

- **`coal_co2`**: Emisiones de CO₂ generadas por el uso de carbón en el país, en millones de toneladas.
- **`coal_co2_per_capita`**: Emisiones de CO₂ de carbón por persona.

### Emisiones Acumulativas de CO₂ por Sector

- **`cumulative_cement_co2`**: Total acumulado de emisiones de CO₂ de la industria del cemento en todos los años hasta el actual, en millones de toneladas.
- **`cumulative_co2`**: Total acumulado de emisiones de CO₂ del país (sin incluir LUC).
- **`cumulative_co2_including_luc`**: Total acumulado de emisiones de CO₂ del país (incluyendo LUC).
- **`cumulative_coal_co2`**: Total acumulado de emisiones de CO₂ por uso de carbón.
- **`cumulative_flaring_co2`**: Total acumulado de emisiones de CO₂ por quemado de gas en antorchas (flaring).
- **`cumulative_gas_co2`**: Total acumulado de emisiones de CO₂ por uso de gas natural.
- **`cumulative_luc_co2`**: Total acumulado de emisiones de CO₂ debidas al cambio de uso de la tierra (LUC).
- **`cumulative_oil_co2`**: Total acumulado de emisiones de CO₂ por uso de petróleo.

### Emisiones de CO₂ por Otros Sectores

- **`flaring_co2`**: Emisiones de CO₂ generadas por el quemado de gas (flaring).
- **`flaring_co2_per_capita`**: Emisiones de CO₂ de flaring por persona.
- **`gas_co2`**: Emisiones de CO₂ generadas por el uso de gas natural.
- **`gas_co2_per_capita`**: Emisiones de CO₂ de gas por persona.
- **`land_use_change_co2`**: Emisiones de CO₂ causadas por cambios en el uso de la tierra, como la deforestación.
- **`land_use_change_co2_per_capita`**: Emisiones de CO₂ de cambio de uso de la tierra por persona.
- **`oil_co2`**: Emisiones de CO₂ generadas por el uso de petróleo.
- **`oil_co2_per_capita`**: Emisiones de CO₂ de petróleo por persona.

### Participación Global de Cada Tipo de Emisión

- **`share_global_cement_co2`**: Participación del país en las emisiones globales de CO₂ de cemento.
- **`share_global_co2`**: Participación del país en las emisiones globales de CO₂.
- **`share_global_co2_including_luc`**: Participación del país en las emisiones globales de CO₂ (incluyendo LUC).
- **`share_global_coal_co2`**: Participación del país en las emisiones globales de CO₂ de carbón.
- **`share_global_cumulative_cement_co2`**: Participación del país en el total acumulado de emisiones de CO₂ de cemento.
- **`share_global_cumulative_co2`**: Participación del país en el total acumulado de emisiones de CO₂.
- **`share_global_cumulative_co2_including_luc`**: Participación del país en el total acumulado de emisiones de CO₂ (incluyendo LUC).
- **`share_global_cumulative_coal_co2`**: Participación del país en el total acumulado de emisiones de CO₂ de carbón.
- **`share_global_cumulative_flaring_co2`**: Participación del país en el total acumulado de emisiones de CO₂ de flaring.
- **`share_global_cumulative_gas_co2`**: Participación del país en el total acumulado de emisiones de CO₂ de gas.
- **`share_global_cumulative_luc_co2`**: Participación del país en el total acumulado de emisiones de CO₂ de LUC.
- **`share_global_cumulative_oil_co2`**: Participación del país en el total acumulado de emisiones de CO₂ de petróleo.
- **`share_global_flaring_co2`**: Participación del país en las emisiones globales de CO₂ de flaring.
- **`share_global_gas_co2`**: Participación del país en las emisiones globales de CO₂ de gas.
- **`share_global_luc_co2`**: Participación del país en las emisiones globales de CO₂ de LUC.
- **`share_global_oil_co2`**: Participación del país en las emisiones globales de CO₂ de petróleo.

### Cambio de Temperatura Atribuido a Gases de Efecto Invernadero

- **`share_of_temperature_change_from_ghg`**: Parte del cambio de temperatura global atribuible a gases de efecto invernadero en el país.
- **`temperature_change_from_ch4`**: Cambio de temperatura causado por las emisiones de metano (CH₄) en el país.
- **`temperature_change_from_co2`**: Cambio de temperatura causado por las emisiones de CO₂ en el país.
- **`temperature_change_from_ghg`**: Cambio de temperatura global total causado por los gases de efecto invernadero (todos los gases).
- **`temperature_change_from_n2o`**: Cambio de temperatura causado por las emisiones de óxido nitroso (N₂O) en el país.
