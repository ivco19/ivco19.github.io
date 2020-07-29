
El grupo multidisciplinario **Arcovid19** busca diseñar herramientas
para el soporte de decisiones frente a la actual pandemia de COVID-19 en
la Argentina y el mundo.

Se centra en 5 ejes de trabajo/productos todos disponibles libre y
gratuitamente.

## Carga rápida de datos 

**Brooks** es una herramienta de software libre destinada a la carga
rápida de datos epidemiológicos desde planillas de cálculo. Está
diseñado para tolerar errores y datos duplicados con relativa facilidad.
**Brooks** también está diseñado para integrar las funcionalidades de
los otros productos.

-   **Descarga:** [*https://github.com/ivco19/brooks*](https://github.com/ivco19/brooks)
-   **Video demo:** [*https://www.youtube.com/watch?v=nuDhyLOc\_og*](https://www.youtube.com/watch?v=nuDhyLOc_og)
-   **Demo online:** [https://brooks-covid19.herokuapp.com/ ](https://brooks-covid19.herokuapp.com/)


## Base de datos oficiales y explotación

Mediante la libreria **Arcovid19** se cura y concilia de manera automatizada la información disponible
en los medios oficiales diariamente para obtener una base de datos
útiles para el soporte de decisiones. También se creó una herramienta
para el análisis y el cálculo de errores de esta base como así también un generador
de escenarios epidemiológios (ver siguiente apartado).

-   **Base de datos:** [*Click aquí para visualizar la base*](https://docs.google.com/spreadsheets/d/e/2PACX-1vTfinng5SDBH9RSJMHJk28dUlW3VVSuvqaBSGzU-fYRTVLCzOkw1MnY17L2tWsSOppHB96fr21Ykbyv/pub) -
    (Descargar para Excel: [*Aquí*](https://github.com/ivco19/libs/raw/master/databases/cases.xlsx))
-   **Herramienta de análisis:**
    [*https://arcovid19.readthedocs.io/*](https://arcovid19.readthedocs.io/en/latest/?badge=latest)
-   **Video demo de la herramienta:**
    [*https://www.youtube.com/watch?v=VBRtnJFF6UQ*](https://www.youtube.com/watch?v=VBRtnJFF6UQ)


## Generación de escenarios epidemiológicos

Se modificó un programa para la generación de escenarios
epidemiológicos, para la búsqueda del aplanamiento de la curva. Esta
herramienta consume los datos generados por Arcovid19 para ajustar sus
resultados al estado actual de la situación del país.

-   **Versión online:** [*https://epacalc-arg.now.sh/*](https://epacalc-arg.now.sh/)
-   **Descarga:**
    [*https://github.com/ivco19/epcalc*](https://github.com/ivco19/epcalc)
-   **Video demo:**
    [*https://youtu.be/-80n4NJxfZA*](https://youtu.be/-80n4NJxfZA)
    
Por otro lado hemos reescrito el codigo de epcalc en con el stack científico de Python
y lo hemos hecho disponible como un backend JSON+CSV. La aplicación completa esta
disponible en [https://github.com/ivco19/epyRba](https://github.com/ivco19/epyRba)
Por otra parte se encuentran disponibles ejemplos para los lenguajes [Javascript](https://github.com/ivco19/epyRba/blob/master/examples/fetch.js) y [Python](https://github.com/ivco19/epyRba/blob/master/examples/fetch.py)

-   **Versión online:** [*https://epyrba.herokuapp.com/*](https://epyrba.herokuapp.com/)
-   **Descarga:**
    [*https://github.com/ivco19/epyrba*](https://github.com/ivco19/epyrba)
    
Tambien dentro de la libreria [Arcovid19](https://arcovid19.readthedocs.io/) implementamos modelos epidemiológicos
compartimentados basados en grafos. Estos modelos poseen una interfaz de exploración web la cual esta diponible online en:

-  **Interfáz en Arcovid19** [https://arcovid19.herokuapp.com/](https://arcovid19.herokuapp.com/)


## Comparación de escenarios epidemiológicos

Utilización de herramientas de visualización para comparar la evolución
de la pandemia en distintos países, teniendo en cuenta sus respectivas
estrategias para prevenir el crecimiento en el número de contagios.
Implementación de un modelo compartimental numérico que permite
introducir las distribuciones estadísticas de los parámetros medidos
para analizar su efecto a largo plazo, teniendo en cuenta las distintas
respuestas al virus en función de la edad de los individuos.

- Proyecto: [https://github.com/ivco19/countries](https://github.com/ivco19/countries)
- Documentación: [https://ivcov19-countries.readthedocs.io](https://ivcov19-countries.readthedocs.io)


----


## Financiaciamiento

Resolucón Rectoral UNDEF `114/2020` - **Soporte a la decisión ante COVID-19**: Se Facilitaran los procesos de soporte a la decisión para aumentar la efectividad y confiabilidad de la respuesta ante la Pandemia de COVID-19 mediante el diseño, ejecución y la mejora de herramientas de software que promuevan la recolección, el resumen, el análisis y el reporte de datos.  	

- Desarrollar una herramienta de software libre destinada a la carga rápida de datos epidemiológicos desde planillas de cálculo.
- Producir, mantener y conciliar de manera automatizada  una base de datos contenedora de las informaciones oficiales, disponibles y diarias para el soporte de decisiones
- Generar escenarios epidemiológicos mediante la implementación de modelos que permitan apreciar el estado actual de la situación del país.
- Realizar un benchmarking para comparar la evolución de la pandemia en distintos países y que permita identificar las mejores prácticas para la prevención del número de contagios, con el propósito de facilitar la transferencia de éstas para los tomadores de decisiones.


> Enlace a la resolución: [PDF](https://github.com/ivco19/ivco19.github.io/raw/master/docs/res_114_20_UNDEFI.pdf)



## Notas de prensa

> Periferia (2020, April 29). Como es la tecnología con la que se analizan los escenarios post-cuarentena. Retrieved April 29, 2020, from http://www.periferiaciencia.com.ar/noticia.php?n=899
>
> [Enlace](http://www.periferiaciencia.com.ar/noticia.php?n=899)

> Pablo Esteban, Página 12 (2020, April 25). Coronavirus: Argentina comparada con Estados Unidos, Brasil y Chile. Retrieved April 29, 2020, from https://www.pagina12.com.ar/261982-coronavirus-argentina-comparada-con-estados-unidos-brasil-y-
>
> [Enlace](https://www.pagina12.com.ar/261982-coronavirus-argentina-comparada-con-estados-unidos-brasil-y-)

> Aldo Lagarto Guizzardi (presentador), Lares, M., & Cabral, J. (entrevistados). (8 de Abril, 2020). Arcovid, el soporte que permite entender el Coronavirus[programa de TV]. Canal12. Artear (productor ejecutivo). El Show del Lagarto. Córdoba, Argentina: EldoceTV (TELECOR SACI)
>
> [Enlace](https://youtu.be/zL3g5-NTP0c)

> Prensa UNC (2020, April 6). Investigadores del Observatorio Astronómico de Córdoba proponen herramientas para ayudar a entender y combatir el coronavirus. Retrieved April 11, 2020, from https://www.unc.edu.ar/comunicaci%C3%B3n/investigadores-del-observatorio-astron%C3%B3mico-de-c%C3%B3rdoba-proponen-herramientas-para
>
> [Enlace](https://www.unc.edu.ar/comunicaci%C3%B3n/investigadores-del-observatorio-astron%C3%B3mico-de-c%C3%B3rdoba-proponen-herramientas-para)

> Mención de Herramientas desarrolladas por el Grupo en:
> Pablo A. González. (2020, Abril 5). Comerse la curva. Revista El gato y la caja. Retrieved April 9, 2020, from https://elgatoylacaja.com.ar/comerse-la-curva/
>
> [Enlace](https://elgatoylacaja.com.ar/comerse-la-curva/)

> Lares, M., & Rubenstein, V. (2020, April 4). Proyecto Arcovid19: Herramientas para ayudar a entender y combatir el 
> Coronavirus. Retrieved April 6, 2020, from https://oac.unc.edu.ar/2020/04/04/proyecto-arcovid19-herramientas-para-ayudar-a-entender-y-combatir-el-coronavirus/
>
> [Enlace](https://oac.unc.edu.ar/2020/04/04/proyecto-arcovid19-herramientas-para-ayudar-a-entender-y-combatir-el-coronavirus/)

> Vázquez A. (2020, April 2). Pandemia de datos II [Episodio 35] [Audio and Video podcast]. from 
> https://avdata99.github.io/cadena-de-datos/s02e35-pandemia-de-datos-ii.html 
>
> [Enlace](https://avdata99.github.io/cadena-de-datos/s02e35-pandemia-de-datos-ii.html)

## Charlas y seminarios

- **Ciclo de charlas sobre propagación y evoluciónde epidemias** Se participó en la primera sesión del ciclo donde se abordó la temática *"Modelos matemáticos de propagación y evolución de epidemias"*. Se conto con la participación de investigadores del IFEG, IATE e IITEMA, entre otros, como disertantes de trabajos donde también colaboran investigadores de
INFIQC y CIQUIBIC. 
    - [Anuncio](https://github.com/ivco19/ivco19.github.io/raw/master/images/seminario20200527.jpeg). 
    - [Video del seminario](https://www.youtube.com/watch?v=pRsd_-DDVHU&feature=youtu.be).
    
- **Seminario en el Grupo de Análisis Numérico y Computación de FaMAF** En este seminario presentamos el trabajo del equipo para el soporte de decisión frente a la pandemia del virus COVID 19 (https://ivco19.github.io). Se describirán brevemente las diferentes líneas de acción generadas (i.e. acceso a bases de datos, visualización, e implementación y análisis de modelos epidemiológicos), así como los problemas sociales en el desarrollo de los mismos.
    - [Video del seminario](https://www.youtube.com/watch?v=TmVsCRS9gKE&feature=youtu.be).

## Miembros del grupo

-   Juan B Cabral (CIFASIS-UNR, IATE-OAC-UNC).
-   Vanessa Daza (IATE-OAC-UNC, FaMAF-UNC).
-   Diego García Lambas (IATE-OAC-UNC, FaMAF-UNC).
-   Marcelo Lares (IATE-OAC-UNC, FaMAF-UNC).
-   Nadia Luczywo (LIMI-FCEFyN-UNC, IED-FCE-UNC, FCA-IUA-UNDEF)
-   Dante Paz (IATE-OAC-UNC, FaMAF-UNC).
-   Rodrigo Quiroga (INFIQC-CFQ, FCQ-UNC).
-   Bruno Sanchez (Department of Physics, Duke University).
-   Federico Stasyszyn (IATE-OAC, FaMAF-UNC).

## Afiliaciones

-   [Centro Franco Argentino de Ciencias de la Información y de Sistemas (CIFASIS-UNR)](https://www.cifasis-conicet.gov.ar/)
-   [Instituto de Astronomía Teórica y Experimental (IATE-OAC-UNC)](http://iate.oac.uncor.edu/)
-   [Facultad de Matemática Astronomía Física y Computación (FaMAF-UNC)](https://www.famaf.unc.edu.ar/)
-   [Laboratorio de Ingeniería y Mantenimiento Industrial
    (LIMI-FCEFyN-UNC)](https://fcefyn.unc.edu.ar/facultad/secretarias/extension/prosecretaria-de-vinculacion-tecnologica/centro-de-transferencia-y-servicios/centro-de-vinculacion-del-centro-de-asesoramiento-matematico-a-procesos-organizacionales/)
-   [Instituto De Estadística Y Demografía - Facultad de Ciencias Económicas (IED-FCE-UNC)](http://www.eco.unc.edu.ar/instituto-de-estadistica-y-demografia)
-   [Department of Physics, Duke University](https://phy.duke.edu/)
-   [Facultad de Ciencias de la Administración (FCA-IUA-UNDEF)](https://www.iua.edu.ar/)
-   [Instituto de Investigaciones en Físico-Química de Córdoba (INFIQC-CONICET)](http://infiqc-fcq.psi.unc.edu.ar/)

### Contacto

[jbcabral@unc.edu.ar](jbcabral@unc.edu.ar)
