# Estructura de estos datos:

A continuación se presentan los datos transcritos de los [Informes EPIDIMIOLÓGICOS entregados por el MINSAL](https://github.com/YachayData/COVID-19/tree/master/fuentes/informes_departamento_epidimiologia) en el formato **EXACTO** que se entrega. Esto quiere decir que para las comunas en que existen menos de 4 casos, se infrorma '-', tal cual lo hace el minsal. El cálculo de los casos reales usando la tasa se realiza después, con la ayuda del script [consolidarCSV.py](https://github.com/YachayData/COVID-19/blob/master/actualizacion/consolidarCSV.py). De esa manera, los consolidados tienen el valor real.

Para las comunas no identificadas se usa el `id_region` y `nombre_region` correspondiente, pero se usa como comuna el nombre `Por determinar`.

- Nombre del archivo: **YYYY-MM-DD-InformeDiarioComunas-COVID19.csv**, donde YYY-MM-DD es la fecha del informe
- Estructura de los datos:
```
 id_region
nombre_region
id_comuna
nombre_comuna
poblacion
casos totales
tasa
```
