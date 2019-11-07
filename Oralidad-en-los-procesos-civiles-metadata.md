Oralidad en los procesos civiles
================================

En este conjunto de datos se detallan los procesos de conocimiento civiles y comerciales de la Provincia de Buenos Aires, que tramitan mediante la oralidad efectiva, detallándose fechas de los procesos tales como el inicio y fin y la forma de resolución, fechas de las audiencias celebradas y sus resultados. 

El proyecto en la provincia de Buenos Aires inició fijándose audiencias preliminares desde agosto de 2016 y a octubre 2018 cuenta con 107 jueces implementando el proceso por audiencias. La generalización de la oralidad civil efectiva en la República Argentina es impulsada por el Ministerio de Justicia y Derechos Humanos de la Nación, de acuerdo a los objetivos de la Estrategia Nacional de Reforma de la Justicia Civil, Res 829/17 MJyDH.

http://datos.jus.gob.ar/dataset/oralidad-en-los-procesos-civiles

Características
---------------

-   **Fecha de Primera Publicación:** 18/10/2018

-   **Tags o Etiquetas:** causas, audiencias, oralidad, procesos civiles, procesos orales, juzgados, conciliación, procesos por audiencias, oralidad civil, Buenos Aires

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Programa Justicia 2020

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Programa Justicia 2020

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Programa Justicia 2020

-   **Grupo:** Instituciones de Justicia

-   **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Oralidad en los procesos civiles - Provincia

-   **Nombre:** oralidad-procesos-civiles-provincia.csv

-   **Descripción del contenido:** se detallan las audiencias de oralidad en procesos de conocimiento civiles y comerciales de la provincia mencionada.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** varía por provincia

### Campos del recurso

-   **provincia_id (string):** código de provincia del juzgado que lleva la causa, según la codificación implementada por INDEC

-   **provincia_nombre (string):** nombre de provincia en la que se encuentra el juzgado que lleva la causa

-   **localidad_nombre (string):** localidad en la que se encuentra el juzgado que lleva la causa

-   **juzgado_numero (int):** número de juzgado en el que se encuentra la causa. Cuando toma el valor 0 significa que se trata de un juzgado de paz

-   **juzgado_tipo (int):** sólo para Santa Fe. Categoría que define a los juzgados según las competencias determinadas en la ley orgánica provincial

-   **causa_id (string):** código que identifica la causa

-   **causa_objeto_litigio_descripcion (string):** objeto por el cual se da inicio a la causa

-   **causa_fecha_recepcion (date):** fecha en que se inicia la causa. Tiene el formato AAAA-MM-DD

-   **causa_fecha_ingreso (date):** fecha en que la causa ingresa al juzgado. Tiene el formato AAAA-MM-DD

-   **audiencia_preliminar_fecha (date):** fecha que se fija para la audiencia preliminar. Tiene el formato AAAA-MM-DD

-   **audiencia_preliminar_resultado (string):** resultado de la audiencia preliminar. Puede tomar los valores:

    -   Concilió en audiencia
        
    -   Concilió previamente

    -   Frustrada
    
    -   Suspendida
    
    -   No concilió
 
-   **apertura_prueba_fecha (date):** fecha de la resolución de apertura prueba. Tiene el formato AAAA-MM-DD

-   **audiencia_vista_causa_fecha (date):** fecha que se fija para la audiencia de vista de causa. Tiene el formato AAAA-MM-DD

-   **audiencia_vista_causa_resultado (string):** resultado de la audiencia vista causa. Puede tomar los valores:

    -   Concilió en audiencia
        
    -   Concilió previamente

    -   Frustrada
    
    -   Suspendida
    
    -   No concilió

-   **llamamiento_autos_fecha (date):** fecha de la resolución de llamamiento autos a sentencia. Tiene el formato AAAA-MM-DD

-   **proceso_finalización_fecha (date):** fecha en que finaliza el proceso. Tiene el formato AAAA-MM-DD

-   **proceso_resultado_descripcion (string):** descripción del resultado del proceso

-   **clase_proceso_descripcion (string):** tipo de proceso con el que tramita la causa


### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Resolución N° 1904/12](http://www.scba.gov.ar/oralidad/pdfs/RC_1904-12.pdf)

[Resolución Nº 829/17 MJyDH](http://servicios.infoleg.gob.ar/infolegInternet/anexos/285000-289999/285767/norma.htm)

[Nueva gestión judicial. Oralidad en los procesos civiles](http://www.saij.gob.ar/docs-f/ediciones/libros/Nueva_gestion_judicial.pdf)

[CONVENIO MARCO DE COOPERACIÓN Y ASISTENCIA TÉCNICA ENTRE EL MINISTERIO DE JUSTICIA Y DERECHOS HUMANOS DE LA NACIÓN Y LA SUPREMA CORTE DE JUSTICIA DE LA PROVINCIA DE BUENOS AIRES](http://www.scba.gov.ar/oralidad/pdfs/Ref3_CONVENIO%20NRO.%20412.pdf)
