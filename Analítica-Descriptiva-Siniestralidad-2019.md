# ANALITICA DESCRIPTIVA DE LAS MUERTES OCURRIDAS EN SINIESTROS VIALES EN EL MUNICIPIO DE MEDELLIN DE LOS AÑOS 2008 A 2019
#
#
>>>>>>>>>### Paolo Andrés Camacho Ramírez
>>>>>>>>>### William
>>>>>>>>>### Michael
###
###
>>>>>### Estudiantes Curso Analitica Predictiva con Python
>>>>>### Convenio Universidad Nacional- Ruta N- Alcaldia de Medellin
#
### Noviembre 3 de 2019
#
#
## Resumen
#

## Tabla de Contenido
#
1.Introducción

>>1.1. Motivación

>>1.2. Metodología

2.Desarrollo

>>2.1. Identificación del problema

>>2.2. Identificación de los datos

>>2.3. Descripción de los datos

>>>2.3.1. Limpieza y resumen

>>>2.3.2. Análisis de los datos

>>>2.3.3. Tratamiento de datos atípicos

>>2.4. Modelación de los datos

>>2.5. Evaluación del modelo

>>2.6. Implementación del modelo

3.Conclusiones

4.Bibliografía
#
#
#
#
## 2.Desarrollo

>## 2.1. Identificación del problema
Según la Organización Mundial de la Salud (OMS) en el mundo mueren 1,24 millones de personas al año por accidentes de tránsito y entre 40 y 50 millones de personas sufren lesiones a causa de estos eventos, lo cual ha aumentado la alerta frente al impacto global en la salud pública y productividad que conllevan los accidentes viales, al punto que ha sido declarado como una “Pandemia”, y representan la primera causa de muerte en la población juvenil de 15 a 29 años de edad y la tercera en la población de 30 a 40 años de edad. Asimismo, las tendencias actuales indican que, de no tomarse medidas urgentes, los incidentes de tránsito se convertirán en la quinta causa de muerte para 2030 (Organización Mundial de la Salud OMS, 2013).

En este sentido, en marzo de 2010, la resolución 64/255 de la Asamblea General de las Naciones Unidas proclamó el periodo 2011–2020 «Decenio de Acción para la Seguridad Vial» con el objetivo de estabilizar y, posteriormente, reducir las cifras previstas de víctimas mortales en accidentes de tránsito en todo el mundo, aumentando las actividades en los planos nacional, regional y mundial.

Siendo Colombia miembro de la ONU, se acogio a las directricez y politicas establecidas en el Decenio de Acción para la Seguridad Vial 2011–2020, para lo cual se expidio la respectiva normatividad que reglamentara la elaboracion de planes estrategicos de seguridad vial en el nivel nacional, departamental, municipal y empresarial; de otro lado se crearon Observatrios de seguridad vial en estos mismos niveles , encargados fundamentalmente de realizar seghuimiento a la evolucion de las metas trazadas endichos planes y adoptar estrategias que redunden en la reduccion de la lesiones y mortalidad en accidentes viales.

Tomando en cuenta la problematica enunciada, se plantea el desarrollo de este proyecto para la creacion de herramietas que permitan tener informacion para apoyar la toma de desciciones y la adopcion de estrategias de intervencion considerando la informacion de  grupos etareos afectados , georreferenciacion e identificacion donde zonas donde las muertes son recurrentes, detectar la incidencia de la alcoholemia, las muertes segun la garvedad, los rangos horarios con mayor numero de muertes, el dia de la semana el mes del año con el mayor numero de muertos
#
#
>## 2.2. Identificación de los datos
Para este proyecto se utilizó la base de datos que transcribe el contratisa UNE, quienes son los encargados de transcribir la información levantada por el guarda de transito en la vía, esta base de datos se viene diligenciando en formato excel desde el año 2008 al 18 de agosto de 2019.  link a los archivos de excel.

La estructura de la tabla en excel es la siguiente:

Orden	|Fecha Ocurrencia	|Hora Ocurrencia	|Fecha Levantamiento	|Spoa	|Expediente	|Clase	|Grupo	|Direccion Ocurrencia	|Municipio	|Lugar de Inspección	|Victima_Nombre	|Victima_Apellido	|Identificacion	|Sexo	|Años	|Condicion	|Vehículo Víctima o vehículo que atropella	|Placa	|Servicio	|Empresa	|Embriaguez 

Se realizo la respectiva anonimización de los datos, procedimiento y codigo que se muestran mas adelante en el numeral


