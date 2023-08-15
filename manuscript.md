---
title: Etapa 2. Ejecución Gobierno SOA del FNA. Incremento 1
keywords:
- SOA
- madurez
- gobierno
- FNA
lang: en-US
date-meta: '2023-08-15'
author-meta:
- Harry Wong, ing.
- Wilson Morales, ing.
- Sergio Andrés Castro Hernandez, ing.
- Viviana M. Martinez, ing.
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Etapa 2. Ejecución Gobierno SOA del FNA. Incremento 1" />
  <meta name="citation_title" content="Etapa 2. Ejecución Gobierno SOA del FNA. Incremento 1" />
  <meta property="og:title" content="Etapa 2. Ejecución Gobierno SOA del FNA. Incremento 1" />
  <meta property="twitter:title" content="Etapa 2. Ejecución Gobierno SOA del FNA. Incremento 1" />
  <meta name="dc.date" content="2023-08-15" />
  <meta name="citation_publication_date" content="2023-08-15" />
  <meta property="article:published_time" content="2023-08-15" />
  <meta name="dc.modified" content="2023-08-15T19:27:57+00:00" />
  <meta property="article:modified_time" content="2023-08-15T19:27:57+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Harry Wong, ing." />
  <meta name="citation_author_institution" content="Arquitecto SOA, Stefanini" />
  <meta name="citation_author" content="Wilson Morales, ing." />
  <meta name="citation_author_institution" content="Software, Aplicaciones" />
  <meta name="citation_author" content="Sergio Andrés Castro Hernandez, ing." />
  <meta name="citation_author_institution" content="SOA, Arquitectura" />
  <meta name="citation_author" content="Viviana M. Martinez, ing." />
  <meta name="citation_author_institution" content="Analista, Proyectos" />
  <link rel="canonical" href="https://hwong23.github.io/fna-dd-f2-pry2-e4/" />
  <meta property="og:url" content="https://hwong23.github.io/fna-dd-f2-pry2-e4/" />
  <meta property="twitter:url" content="https://hwong23.github.io/fna-dd-f2-pry2-e4/" />
  <meta name="citation_fulltext_html_url" content="https://hwong23.github.io/fna-dd-f2-pry2-e4/" />
  <meta name="citation_pdf_url" content="https://hwong23.github.io/fna-dd-f2-pry2-e4/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://hwong23.github.io/fna-dd-f2-pry2-e4/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/fna-dd-f2-pry2-e4/v/420be7b0e0aa78ed3abf3af3db98fa286204a5bd/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/fna-dd-f2-pry2-e4/v/420be7b0e0aa78ed3abf3af3db98fa286204a5bd/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/fna-dd-f2-pry2-e4/v/420be7b0e0aa78ed3abf3af3db98fa286204a5bd/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.bib
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...

---
title: E-Service Etapa 2. Arquitectura de Referencia SOA 2.0 del FNA
geometry:
  - top=1in
  - bottom=1in
fignos-cleveref: True
fignos-plus-name: Fig.
fignos-caption-name: Imagen
tablenos-caption-name: Tabla
...


<small><em>Los productos de esta etapa ([Web](https://hwong23.github.io/fna-dd-f2-pry2-e4/v/420be7b0e0aa78ed3abf3af3db98fa286204a5bd/))
están basados en el resultado de la consultoría "Arquitectura E-Service",
[Sharepoint STEF@420be7b](https://stefaninilatam.sharepoint.com/:f:/r/sites/PROYECTOARQUITECTURAE-SERVICEFNA/Documentos%20compartidos/General/Repositorio%20SOA/Procesos%20Fase%20II/181-2020.%20E-SERV.%20Fase%202-ETAPA%200.%20docx?csf=1&web=1&e=BiNcBP)
del August 15, 2023.
</em></small>

|    **Versión** del producto 1.420be7b de 15 Aug 2023




<br>

## Autores



+ **Harry Wong, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [e_hwong](https://github.com/e_hwong)
    <br>
  <small>
     Arquitecto SOA, Stefanini
  </small>

+ **Wilson Morales, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [wmorales](https://github.com/wmorales)
    <br>
  <small>
     Software, Aplicaciones
  </small>

+ **Sergio Andrés Castro Hernandez, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [fhernandez](https://github.com/fhernandez)
    <br>
  <small>
     SOA, Arquitectura
  </small>

+ **Viviana M. Martinez, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [vmmartinez](https://github.com/vmmartinez)
    <br>
  <small>
     Analista, Proyectos
  </small>


::: {#correspondence}
✉ — Enviar mensajes a Harry Wong, ing. \<e_hwong@stefanini.com\>.


:::

<br>



## Objetivo del Documento
Entrega de los productos de la Etapa 2, PR11 y PR12, del proyecto PR02, Arquitectura de Referencia SOA 2.0 del FNA, flujos de trabajo y personas que ejercitan y conforman (cumplen) con el gobierno SOA del FNA a desplegar a cargo de la oficina de arquitectura.


##  Control de Cambios {.page_break_before}
| Tema           | PRY02 Arquitectura de Referencia SOA 2.0 del FNA      |
|----------------|----------------------------|
| Palabras clave | SOA, E-Service, FNA, Análisis de brecha, GAP, Comparativa              |
| Autor          |                            |
| Fuente         |                            |
| Versión        | 1.420be7b del 15 Aug 2023 |
| Vínculos       | [N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md) |

<br>

<br>

<div style="page-break-before: always;"></div>



## Contenidos
\toc



---
prnombre: "Análisis de impacto y modelos actualizados de los ítems de arquitectura"
...

<div style="page-break-before: always;"></div>
\newpage

>    E-Service. Fase II
>
>    PRY02. Arquitectura de Referencia SOA 2.0 del FNA. Contenido de los Productos Contractuales
>
>    Contrato 1812020
>
>    FNA, Stefanini
>
>    15 Aug 2023
>
>    **Versión** 1.420be7b

<br>

# Producto 16: PR16. Análisis de impacto y modelos actualizados de los ítems de arquitectura
Similar al ejercicio del producto 6, Modelos actualizados de los ítems de arquitectura impactados (PR06), del proyecto PRY01 de esta misma consultoría, en este producto hacemos lo propio respecto de los modelos de la arquitectura de referencia 2.0 del FNA. Por tanto, en este producto organizamos y consolidamos en el depósito de arquitectura del FNA (propuesto por esta misma consultoría) la información de los modelos de la arquitectura de referencia SOA 2.0 del FNA. A este lo complementa el análisis de impacto inicial que trate sobre las implicaciones de la adopción de los cambios funcionales y tecnológicos enunciados por esta arquitectura camino a ser el mapa de viaje de la transformación de las capacidades de negocio y de arquitectura del FNA (ver [Producto 11](<../../fna-dd-f2-pry2-e1/content/11.detalle roles recursos.md>) de este proyecto).

Al repositorio línea base entregado por el proyecto 1 (anterior a este) agregamos nuevos modelos a razón de la  arquitectura de referencia y del ejercicio de este producto.

| Tipo de Entrada      |          |
|----------------------|---------:|
| Arquitectura         | 12       |
| Funcional            | 4        |
| **Total Contenidos** | **1311** |

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto PRY01, Gobierno SOA: desarrollo, gestión, gobierno de arquitectura y adopción.

<br>

## Justificación
Uno de los objetivos nominales, y objeto del proyecto actual, es la creación de la primera versión de la arquitectura de referencia SOA del FNA proyecto. Objetivo que se pliega al de _aumentar la relevancia de los modelos de arquitectura del Fondo Nacional_. En este proyecto 2 de Fase, II E-Service, los modelos son instrumentos de encuentro para el entendimiento, análisis, y comunicación entre actores, como ingenieros, arquitectos, proveedores, líderes de grupo. Se cumple también la máxima de proyectos anteriores de esta misma consultoría: los modelos, en este caso de la arquitectura de referencia, son por el sujeto principal, y la evidencia, de la existencia del gobierno. Por estas razones es que los modelos de referencia SOA 2.0 creados aquí tienen la importancia tal para ser entregados en contribución al repositorio de arquitectura de la empresa.

## Contenidos
1. Definición de los Bloques de Construcción Abstractos del FNA (BCAF)
1. Métodos para la gestión y evolución de los Bloques de Construcción Abstractos del FNA (BCAF)
1. Listado de Bloques de Construcción Abstractos del FNA (BCAF)
1. Utilización de los Bloques de Construcción Abstractos en el FNA

<br>

## Criterios de Aceptación
1. Detalle de ítems de la línea base de arquitectura de referencia 2.0 del FNA
1. Repositorio de arquitectura del FNA, versión 0.5, actualizado con arquitectura de referencia
1. Consideraciones para la adopción y puesta en marcha de los cambios en las arquitecturas del FNA
1. Anexo. Herramienta de navegación del repositorio de arquitectura del FNA versión 0.3

<br>

## Repositorio de Arquitectura del FNA, versión 0.5
![Artefactos del repositorio de arquitectura del FNA.](images/repofna.png){#fig: width=}

_Fuente: Diagnóstico SOA. E-Service (2022)._


## Modelo de Implementación del PRY02
![Plan de Implementación del Proyecto Arquitectura de Referencia SOA 2.0 del FNA (PRY02), 2023. Junio 2023 a julio 2023](images/pry2e4.png){#fig: width=}

_Fuente: Elaboración propia._

<br>


---
prnombre: "Ítems de arquitectura incrementados en ejecución"
...

<div style="page-break-before: always;"></div>
\newpage

>    E-Service. Fase II
>
>    PRY02. Arquitectura de Referencia SOA 2.0 del FNA. Contenido de los Productos Contractuales
>
>    Contrato 1812020
>
>    FNA, Stefanini
>
>    15 Aug 2023
>
>    **Versión** 1.420be7b

<br>

# Producto 7: PR17. 
Resultado de las primeras actividades del proyecto actual, PRY02, es la creación de modelos dedicados a la arquitectura de referencia SOA 2.0 del FNA. En este producto, PR17, , realizamos la entrega de estos modelos de la consultoría dedicadas a la organización de la información de arquitectura de referencia e ingeniería, instrumentos necesarios todos para la toma de decisiones y comparativas del futuro de la empresa. 

Esta información de ingeniería en la forma de modelos se suma a la entrega producto 06, Modelos actualizados de los ítems de arquitectura impactados por el proyecto (PR06) del proyecto 1, Gobierno SOA del FNA, a la que llamamos la _línea base de arquitectura del FNA_, que funciona como un inventario inicial de modelos equiparable a un repositorio de arquitectura, versión 0.1.

A este producto del proyecto, PRY02, y en virtud de las actividades desarrolladas aquí (las cuales han actualizados la línea base de este repositorio) le corresponde hacer entrega de estas modificaciones al FNA.

<br>

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto PRY02, Arquitectura de Referencia FNA: desarrollo, gestión, gobierno de arquitectura y adopción.

<br>

## Justificación
Uno de los objetivos nominales de la gestión de la arquitectura de referencia SOA del FNA, objeto de este proyecto, es _aumentar la relevancia de los modelos de arquitectura de la empresa_. En este proyecto (PRY02), el conjunto de modelos que conforman la arquitectura de referencia 2.0 del FNA son instrumentos de evolución y de justificación de esta. A partir de estos modelos es posible también devenir análisis, estimaciones comparativas todas acciones necesarias para el proceso de arquitectura del FNA (definido en el proyecto 1 de esta consultoría). Por último, todo esta información debe ser debidamente comunicada a todos los actores (ingenieros, arquitectos, proveedores, líderes de grupo). 

Los modelos de arquitectura de referencia 2.0 del FNA son también sujetos del gobierno, lo cual articula a ambos proyectos, el de gobierno (PRY01) con este.

## Contenidos
1. Detalle de ítems de arquitectura de referencia SOA 2.0  del FNA
1. Modelos actualizados del repositorio de arquitectura del FNA versión 0.3
1. Herramienta de navegación del repositorio de arquitectura del FNA

<br>

## Criterios de Aceptación
* Repositorio de arquitectura del FNA, actualizado, versión 0.3
* Herramienta de navegación del repositorio de arquitectura del FNA

<br>

## Repositorio de Arquitectura del FNA, versión 0.1
![Artefactos del repositorio de arquitectura del FNA.](images/repofna.png){#fig: width=}

_Fuente: Diagnóstico SOA. E-Service (2022)._


## Modelo de Implementación del PRY02
![Plan de Implementación del Proyecto Arquitectura de Referencia SOA 2.0 del FNA (PRY02), 2023. Junio 2023 a julio 2023](images/pry1gobierno.jpg){#fig: width=}

_Fuente: Elaboración propia._

<br>


<div style="page-break-before: always;"></div>
\newpage

# Referencias {.page_break_before}
<!-- Explicitly insert bibliography here -->
<div id="refs">@eservices1-22 @eservices3-22 @eservices4-22 @eservices5-23 @eservices6-12 @eservices7-23 @bptrends07
</div>



