Para la primera clase del Semillero de Investigación en Python, Inteligencia Artificial y Datos (SIPIAD), te recomiendo proponer preguntas que conecten las necesidades del Bajo Cauca antioqueño con el uso de datos, la programación en Python y, progresivamente, la Inteligencia Artificial.

El propósito no es que los estudiantes construyan un modelo de Machine Learning desde la primera sesión, sino que aprendan a pensar como investigadores: formular una pregunta delimitada, identificar qué datos necesitan, reconocer dónde conseguirlos y evaluar si es posible responderla con evidencia.
1. Ideas de preguntas de investigación para el Bajo Cauca
Seleccionadas para estudiantes que comienzan a aprender Python y ciencia de datos.









A. Salud pública

Datos epidemiológicos y ambientales
1. ¿Cómo han variado los casos reportados de dengue en Caucasia entre 2015 y 2025?
2. ¿Qué relación existe entre la precipitación mensual y los casos reportados de dengue en el Bajo Cauca?
3. ¿Se observan patrones estacionales en los registros de enfermedades transmitidas por vectores?
4. ¿Qué variables meteorológicas podrían contribuir a anticipar periodos de mayor riesgo epidemiológico?












B. Clima y medioambiente

Series de tiempo y predicción
5. ¿Cómo ha cambiado la precipitación anual en las estaciones meteorológicas disponibles del Bajo Cauca durante los últimos 15 años?
6. ¿Qué patrones estacionales se identifican en las temperaturas registradas en Caucasia?
7. ¿Qué relación existe entre la precipitación y el nivel de los ríos en periodos para los cuales existan registros comparables?
8. ¿Qué tan bien puede un modelo sencillo predecir la precipitación diaria a partir de sus valores anteriores?












C. Educación

Aprendizaje y permanencia educativa
9. ¿Cómo ha evolucionado la matrícula escolar en los municipios del Bajo Cauca durante los últimos diez años?
10. ¿Qué relación existe entre asistencia y desempeño académico en un conjunto de datos escolares autorizado y anonimizado?
11. ¿Qué temas matemáticos presentan mayores dificultades en los resultados agregados de evaluaciones disponibles?
12. ¿Cómo se relacionan el acceso a Internet y la disponibilidad de dispositivos con las oportunidades de aprendizaje digital?












D. Agricultura y economía rural

Datos productivos y modelos predictivos
13. ¿Cómo se relacionan las variaciones de precipitación con el rendimiento de los cultivos de arroz?
14. ¿Qué variables permiten explicar mejor las variaciones de producción agrícola entre periodos?
15. ¿Qué patrones temporales se observan en los precios de productos agrícolas con registros disponibles?
16. ¿Es posible estimar el rendimiento de un cultivo usando variables meteorológicas y datos históricos de producción?












E. Movilidad y territorio

Observación, mapas y datos urbanos
17. ¿En qué horarios se concentra el flujo vehicular en determinados puntos de Caucasia?
18. ¿Qué sectores presentan mayores tiempos de desplazamiento hacia servicios educativos o de salud?
19. ¿Cómo varían los tiempos de viaje entre temporadas secas y lluviosas en rutas previamente definidas?












F. Biodiversidad y recursos naturales

Datos ecológicos y análisis espacial
20. ¿Cómo varía el número de especies de aves observadas entre sitios y temporadas con registros disponibles?
21. ¿Qué factores ambientales se relacionan con la presencia registrada de determinadas especies?
22. ¿Qué patrones espaciales se observan en los registros públicos de cobertura vegetal y transformación del territorio?



Estas son propuestas de investigación, no afirmaciones de que exista una relación causal ni de que todos los datos estén disponibles. La viabilidad de cada pregunta debe verificarse antes de iniciar el proyecto.
2. ¿Qué datos necesitarían para responder las preguntas?
Esta es la parte central de la actividad. Puedes pedirles que completen una ficha como la siguiente.
Pregunta de investigación	Datos necesarios	Posibles fuentes
¿Cómo varía el dengue con la precipitación?	Casos por fecha y municipio; precipitación por fecha y estación	Instituto Nacional de Salud (INS) e IDEAM.  portalsivigila.ins.gov.co +1
¿Cómo han cambiado las lluvias en Caucasia?	Fecha, precipitación, estación y datos faltantes	Catálogo de estaciones del IDEAM.  IDEAM
¿Cómo ha evolucionado la matrícula escolar?	Matrícula por año, municipio, nivel educativo y otras variables disponibles	Datos Abiertos del Ministerio de Educación.  Ministerio de Educación Nacional
¿Cómo se relaciona la lluvia con la producción agrícola?	Precipitación, cultivo, área sembrada, producción y rendimiento	IDEAM y datos abiertos del Ministerio de Agricultura.  IDEAM +1
¿Cómo cambia la diversidad de especies entre sitios?	Especie, ubicación, fecha y número de observaciones	Registros de biodiversidad y observaciones de campo verificadas.
¿Qué factores se relacionan con los tiempos de desplazamiento?	Origen, destino, hora, duración, condiciones de la vía y clima	Observaciones de campo y registros institucionales disponibles.
Importante: encontrar un portal no garantiza que exista una base con todas las variables, el periodo o la resolución geográfica que necesita el proyecto. Los estudiantes deben comprobar la disponibilidad y calidad de los datos antes de comprometerse con una pregunta.
3. Mi recomendación: comenzar con tres preguntas prioritarias
Para una primera sesión en la que los estudiantes están aprendiendo a instalar Python y utilizar Jupyter, elegiría estas tres opciones.
Opción 1 · Recomendada
¿Cómo ha variado la precipitación mensual en las estaciones meteorológicas disponibles del Bajo Cauca antioqueño durante los últimos diez años?

Por qué elegirla

Es una introducción directa a las series de tiempo, las estadísticas descriptivas y la visualización. Permite comenzar con Python sin necesidad de entrenar un modelo de IA.

Variables iniciales
- Fecha y mes.
- Nombre o código de la estación.
- Precipitación mensual.
- Número de observaciones faltantes.
Primera aplicación con Python

Cargar un archivo CSV con pandas, calcular promedios y totales mensuales, y construir una gráfica temporal.

Opción 2 · IA y salud pública
¿Qué relación existe entre la precipitación mensual y los casos reportados de dengue en Caucasia durante un periodo con datos comparables?

Por qué elegirla

Integra dos fuentes de datos y permite avanzar desde la estadística descriptiva hacia el análisis de correlación y, más adelante, la predicción de riesgo.

Variables iniciales
- Mes y año.
- Precipitación acumulada.
- Casos reportados de dengue.
- Datos faltantes y cambios en los sistemas de registro.
La correlación no demostraría causalidad. Además, las diferencias en los tiempos de respuesta epidemiológica y en la disponibilidad de datos deben considerarse.

Opción 3 · Educación matemática
¿Qué dificultades de aprendizaje matemático aparecen con mayor frecuencia en los registros agregados de evaluación de estudiantes de educación básica de una institución del Bajo Cauca?

Por qué elegirla

Conecta la formación matemática con la práctica docente y permite construir indicadores, tablas y visualizaciones antes de explorar modelos predictivos.

Variables iniciales
- Tema matemático evaluado.
- Número de respuestas correctas e incorrectas.
- Grado escolar.
- Tipo de pregunta.
Requiere autorización para acceder a los registros y precauciones para evitar la identificación de estudiantes.

4. Ficha interactiva para la discusión en parejas
Puedes proyectar esta ficha durante la clase o pedir a cada pareja que la complete en su cuaderno.
Nuestra primera pregunta de investigación
1. Área temática
Salud pública

Clima y medioambiente

Educación

Agricultura y economía

Movilidad

Biodiversidad


2. Pregunta de investigación¿Cómo ha variado la precipitación mensual en las estaciones meteorológicas disponibles del Bajo Cauca durante los últimos diez años?

3. ¿Qué datos necesitamos?Fecha, precipitación mensual, código de estación y datos faltantes

4. ¿Dónde podríamos obtenerlos?

5. ¿Cómo comenzaríamos el análisis?
Estadística descriptiva y visualización

Comparación de grupos

Análisis de series de tiempo

Machine Learning


6. Principal dificultad prevista
Disponibilidad y calidad de los datos

Aprender las herramientas de Python

Definir una pregunta delimitada

Privacidad y permisos


  Copiar ficha completadaDesarrollar la propuesta con ChatGPT
5. Cierre pedagógico de la actividad
Para concluir, pediría a cada pareja que exponga su propuesta en dos minutos y responda estas tres preguntas:
1. Relevancia: ¿a quién le serviría conocer la respuesta y por qué?
2. Viabilidad: ¿existen datos suficientes para responderla de manera responsable?
3. Computación: ¿qué tarea concreta podría realizar Python para ayudarnos a responderla?
Mi recomendación es que las parejas comiencen con preguntas descriptivas, basadas en datos accesibles. Después, a medida que aprendan pandas, visualización, estadística y validación de modelos, podrán evolucionar hacia proyectos de Machine Learning y Deep Learning con mayor rigor científico.