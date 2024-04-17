## PROYECTO INDIVIDUAL NUMERO 2  
 ## DATA-SCIENCE - PART TIME ##
### Analisis sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021 ###

### Trabajo a desarrollar ###
>

>Se nos solicita tomar el Rol de Data-Analyst para la elaboracion de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales.

>Para ello, nos disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021, provisto por el [Observatorio de Movilidad y Seguridad Vial (OMSV)](https://buenosaires.gob.ar/movilidad/plan-de-seguridad-vial/observatorio-de-movilidad-y-seguridad-vial)

>Este dataset se encuentra en formato xlsx y contiene dos hojas llamadas: hechos y víctimas. Asimismo, observarán que incluye otras dos hojas adicionales de diccionarios de datos, que les podrá servir de guía para un mayor entendimiento de la data compartida.

### Contexto⚠️ ###
>Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

>En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país. Los informes del Sistema Nacional de Información Criminal (SNIC), del Ministerio de Seguridad de la Nación, revelan que entre 2018 y 2022 se registraron 19.630 muertes en siniestros viales en todo el país. Estas cifras equivalen a 11 personas por día que resultaron víctimas fatales por accidentes de tránsito.

>Buenos Aires es la capital y ciudad más poblada de la República Argentina. La superficie de la Ciudad es algo superior a los 200 km2 y su perímetro, 60 km. Los habitantes que residen en ella, están distribuidos en barrios que, desde el punto de vista político-administrativo, se agrupan en quince comunas. La densidad de la población es de más de 15.000 habitantes por kilómetro cuadrado. Las zonas centro y norte son los espacios territoriales más densamente poblados.Página de la ciudad La población de la ciudad, según el Censo de 2022 es de 3 120 612 habitantes.Indec Solo en 2022, se contabilizaron 3.828 muertes fatales en este tipo de hechos. Los expertos en la materia indican que en Argentina es dos o tres veces más alta la probabilidad de que una persona muera en un siniestro vial que en un hecho de inseguridad delictiva.

Por todo ello, el estudio del problema para la prevención y disminución de Siniestros viales es escencialmente importante para las autoridades.

### Analisis de datos (EDA) ###

> Con la Bases de Víctimas Fatales en Siniestros Viales que se encuentra en formato de Excel y contiene dos pestañas de datos:

>>HECHOS: que contiene una fila de hecho con id único y las variables temporales, espaciales y participantes asociadas al mismo.

>>VICTIMAS: contiene una fila por cada víctima de los hechos y las variables edad, sexo y modo de desplazamiento asociadas a cada víctima. Se vincula a los HECHOS mediante el id del hecho. En este [documento](NOTAS_HOMICIDIOS_SINIESTRO_VIAL.pdf) se detallan todas las definiciones manejadas en los datos y en el desarrollo de este proyecto.

> Mediante los pasos siguientes se da tratamiento a los grupos de datos:

    -Importación de librerías y carga de datos
    -Verificación de tipo de datos
    -Verificación de duplicados
    -Verificación de nulos
    -Análisis de datos
    -Estadística descriptiva
    -Serie de tiempo, tendencias y estacionalidad
    -Relación entre tipos de eventos
    -Localizaciones
    -Tipos de víctimas
    -Conclusiones para cada analisis

### Presentacion Dashboard en PowerBI ###

> Realizamos nuestra presentacion de los analisis realizados con la herramienta de PowerBI con el siguiente esquema:

    Portada: presentación general
    Eventos: presentacion principales grupos de víctimas y causantes
    Estacionalidad: presentacion Serie temporal de eventos
    Ubicacion geografica: presentacion mapa interactivo por comunas de la ciudad de Buenos Aires
    KPI´s: presentacion de los distintos indicadores propuestos

Podemos acceder a la presentacion [aqui](Proyecto2.pbix)


### Conclusiones ###

> A partir del análisis realizado anteriormente obtenemos las siguientes conclusiones:
 Las victimas fatales por siniestros de tránsito entre los años 2016 a 2021 fueron 717 personas.
 Que la franja horaria de mayor problemática es la del ingreso laboral (5-9h), la del almuerzo (12-14h) y la del regreso a casa(17-18h); aunque durante los fines de semana (Sábado y Domingo), los accidentes se manifiestan en los horarios de salidas nocturnas (3-7h). 
 Las víctimas son en un 76% Masculinas, y sus edades entre el rango etario de 20-40 años.
 Además en los siniestros de Masculinos los mayores casos se dan en su rol como Conductor.
 Los tipos de vehículos más frecuentes con Víctimas son las Motos y luego los Peatones.
 Los Acusados los vehículos más frecuentes son Autos, Colectivos y cargas.
 En cuanto a el lugar donde se producen los siniestros, las Avenidas a lo largo de los años han sido los espacios de mayor cantidad de siniestros.
 Se observo un patrón en relación con la variable Edad y Sexo. Donde los Masculinos de entre 20 a 40 años.

>Continuar con campañas de prevención, educacion vial, controles y el plan seguridad propuesto por el observatorio.


