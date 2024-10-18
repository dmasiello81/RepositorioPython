# Problemas a resolver


**Descripción General**

Este proyecto consiste en una aplicación interactiva de análisis de datos, utilizando diferentes librerías de visualización y manipulación de datos en Python. La aplicación permite cargar y procesar conjuntos de datos, y genera gráficos interactivos y mapas dinámicos para ayudar en la toma de decisiones basada en datos.
La aplicación está construida sobre Streamlit, lo que permite a los usuarios interactuar con los datos y obtener insights visuales en tiempo real.
El objetivo es ofrecer una herramienta accesible para el análisis de datos de forma intuitiva y visualmente atractiva.

## Origen, razon y datos
**Origen**

La fuente de datos trabajada son los microdatos de la Encuesta Continua de Hogares (ECH), Primer semestre 2024 del Instituto Nacional de Estadística (INE) estos datos ofrecen una representación detallada y precisa de la realidad socioeconómica de los hogares en el país. Los microdatos permiten analizar las características de las viviendas y de las personas en términos de ingresos, educación, empleo, y composición familiar, entre otros aspectos, brindando información confiable para realizar estudios que ayuden en la toma de decisiones, formulación de políticas públicas y seguimiento de tendencias en distintos sectores.

**Razón**

Ofrece un conjunto amplio y detallado de información que permite analizar aspectos clave como el empleo, los ingresos, la educación, las características de la vivienda y la estructura de los hogares. Estos datos son fundamentales para:

Realizar análisis sociodemográficos y socioeconómicos: La ECH facilita el estudio de la situación de los hogares en diferentes departamentos del país, permitiendo identificar patrones y tendencias en variables como la composición de los hogares, la situación laboral y los ingresos.

Tomar decisiones informadas: Los datos ayudan a formular políticas públicas más efectivas, al proporcionar un diagnóstico actualizado sobre las condiciones de vida de la población.

Seguimiento de cambios sociales: Al ser una encuesta continua, permite comparar los resultados de diferentes períodos, identificando cambios y tendencias en la estructura social y económica del país.

**Datos** 

Los microdatos de la ECH contienen información detallada a nivel individual y de hogar, incluyendo variables como:

Identificación geográfica: Departamento, localidad, zona, etc.

Composición del hogar: Número de personas, edades, y relaciones entre sus miembros.

Datos socioeconómicos: Ingresos, nivel educativo, situación laboral, etc.

Condiciones de la vivienda: Tipo de vivienda, acceso a servicios básicos, etc.

Este tipo de datos es esencial para crear gráficos, análisis y resúmenes que proporcionen una visión clara de las características y condiciones de los hogares uruguayos en 2024.

**Fuentes utilizadas**

https://www.ine.gub.uy/Anda5/index.php/catalog/757/get-microdata

https://www.ine.gub.uy/Anda5/index.php/catalog/757/data-dictionary/F11?file_name=ECH_semestre1_seguimiento_2024


## Diccionario de variables utilizadas

**nom_dpto** Nombre del departamento

**NOM_LOC_AGR_13** Nombre de las localidades agrupadas donde se releva la ECH

**E27** EDAD Años cumplidos

**E26** SEXO 
Sexo de la persona siendo 1 hombre, 2 mujer

*NIVEL EDUCATIVO*

**NIV_EDU**  1 CB incompleto o menos / 2 CB completo o EMS incompleta / 3 Sec. completa o terciaria incompleta / 4 Terciario completo o posgrado 

*ASCENDENCIA ÉTNICO-RACIAL*

**E29_1** 1 = Sí / 2 = No Afro o negra

**E29_2**  1 = Sí / 2 = No Asiática o amarilla

**E29_3**  1 = Sí / 2 = No Blanca 

**E29_4**  1 = Sí / 2 = No Indígena 

**E29_5**  1 = Sí / 2 = Otra

*INTEGRANTES DEL HOGAR*

**D23** Nº Cantidad de personas de 14 o más años MENORES DE 14 AÑOS 

**D24** Nº Cantidad de personas menores de 14 años TOTAL DE PERSONAS DEL HOGAR 

**D25** Nº Cantidad total de personas del hogar 

## Integrantes del Grupo Team Sitemas

Rodrigo Perez

Martin Filippini

Diego Masiello



