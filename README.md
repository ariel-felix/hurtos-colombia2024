## Hurto a personas - Colombia 2024

#### Objetivo

Después de una larga trayectoria estudiando el curso de Power BI en la Universidade dos Dados, quise practicar lo que he aprendido y también buscar nuevas herramientas como el Figma para mejorar la estética visual de mis presentaciones. 

Este dashboard fue creado con el objetivo que presentar los casos de hurto a personas en Colombia registrados durante el año 2024. La visualización permite el análisis por ciudad, fecha, día de la semana, modalidad del hurto y otras variables relevantes. 

#### Fuente de Datos

Origen: https://www.policia.gov.co/estadistica-delictiva

Formato: Archivo CSV

Campos principales:

Armas Medios: Fecha del hurto

Departamento: Departamento del incidente

Municipio: Municipio del incidente

Fecha hecho: Fecha del incidente

Género: Perfil de la persona involucrada en el incidente

Agrupa Edad Persona: Grupo según edad de la persona (AdultoS, Adolescentes, Menores o No informados)

Cantidad: Cantidad de hurtos en el día

#### Secciones del Dashboard

* Início (capa)

* Visión General (Total de hurtos en el año, Media Mensual de Hurtos, Perfil, Tipo de armas utilizadas, Cantidad de hurtos por municipio y departamento y Filtros por mes y departamento.

* Análisis Pareto del tipo de Arma/Medios

* Análisis temporal - Hurtos separados por mes, día de la semana y día.

#### Transformación y Limpieza de Datos

* Detección de tipo de datos y formatación general;

* Corrección de errores ortográficos o inconsistencias en modalidad y ciudad;

* Imputación de valores nulos a NO INFORMADO;

* Exclusión de colunas que no serían utilizadas;

* Creación de columnas auxiliares: Creación de una columna dimensión Calendar (año, date, mes, día, día_semana, número_mes, trimestre);

* Creación de Medidas auxiliares: Total Hurtos, Media Mensual de hurtos, Porcentaje Acumulado.

#### Herramientas utilizadas
Figma para el Visual;

Power BI Desktop para construcción del dashboard;

Power Query para tratamiento de datos;

DAX para medidas.

#### Visualización del Informe
![image](https://github.com/user-attachments/assets/2922f0d3-90ca-4796-86e7-af5a777fe1c8)

1.Visualización General

![image](https://github.com/user-attachments/assets/33285908-afcc-43b1-81c0-bcd0526d5a1e)
2. Gráfico Pareto de tipo de armas.

![image](https://github.com/user-attachments/assets/68a1cff2-d72b-40a0-acc7-219671b0e5ac)
3. Visualización de distribución temporal



#### Resultados

* Elevado volumen mensual sugiere necesidad de acciones continuas: Con un promedio superior a 26.000 hurtos mensuales, el fenómeno demuestra ser persistente y de gran magnitud. Esto exige el desarrollo de políticas públicas sostenidas de prevención y vigilancia en las zonas más afectadas, con un enfoque en reducción del delito y protección ciudadana.

* El 58% de los hurtos son cometidos por hombres, aunque las mujeres también tienen una participación significativa: Los datos revelan que el 58% de las personas que cometen hurtos son hombres, mientras que el 42% son mujeres. Este hallazgo abre la posibilidad de investigar motivos sociales y económicos diferenciados por género, y reforzar las estrategias de prevención desde una perspectiva más integral.

* Adultos son el grupo etario más involucrado en hurtos: El 98,25% de los casos son cometidos por adultos, seguido por adolescentes (1,49%) y menores de edad (0,16%). Esto refuerza la necesidad de analizar factores estructurales que impulsan el delito en la población adulta, como desempleo, exclusión social y economía informal.

* Alta concentración geográfica de hurtos en grandes centros urbanos: Las ciudades de Bogotá, Medellín y Cali, siendo las más pobladas del país, concentran el mayor número de hurtos. Además de su tamaño poblacional, esto puede estar relacionado con altos niveles de movilidad urbana, comercio informal y desigualdades socioeconómicas. Por otro lado, la baja presencia institucional en zonas rurales y periféricas, en parte debido a la actividad de grupos armados ilegales, podría generar subregistro en departamentos con menor densidad urbana.

* La modalidad más común no involucra violencia directa: El 77,8% de los hurtos se realiza sin el uso de armas ni violencia explícita, lo cual indica oportunidades para intervenciones de prevención situacional: mejor iluminación, instalación de cámaras, diseño urbano seguro y presencia estratégica de autoridades.
Modalidades menos frecuentes pero peligrosas —como el uso de escopolamina o llave maestra— requieren campañas de sensibilización e investigación criminal especializada, dado su potencial de daño y vínculo con redes organizadas.

* Picos de hurtos en días específicos podrían estar ligados a pagos o eventos sociales: Los días 1, 15 y 16 concentran el mayor número de reportes, posiblemente vinculados a fechas de pago de salarios, actividades comerciales o eventos especiales. Esto permite planificar acciones preventivas puntuales en torno a estos días clave.

* Los fines de semana registran más hurtos: Los hurtos aumentan notablemente los sábados y viernes, lo que sugiere mayor vulnerabilidad durante periodos de alta movilidad social, eventos masivos y consumo de alcohol. Las estrategias de seguridad podrían priorizar estos días con patrullajes y control en zonas de ocio.

* Enero y agosto son los meses más críticos: Estos meses podrían coincidir con temporadas de vacaciones, regreso a clases o eventos estacionales. También podrían reflejar una menor operatividad de las fuerzas de seguridad en ciertas épocas. Este patrón permite planear refuerzos policiales temporales y campañas preventivas estacionales.


#### Mejorías

* Agregar datos de años anteriores para análisis histórico;

* Cruce de datos con variables socioeconómicas.





