Análisis de datos: Diagnóstico de enfermedades al corazón
=========================================================

Contexto
--------

 El objetivo de este proyecto es analizar y diagnosticar enfermedades cardíacas utilizando datos clínicos y de salud recopilados de pacientes. La información se recopila a través de varios parámetros, y se busca identificar patrones y relaciones entre estos parámetros.

Conjunto de datos
-----------------

 **Edad (age):** La edad de las personas analizadas se registra en años.  
 **Género (genre):** Se registra el género de cada individuo, ya sea masculino o femenino.  
 **Tipo de Dolor en el Pecho (Chest Pain Type):** Esta variable indica el tipo de dolor en el pecho que los pacientes experimentan. Se pueden registrar diferentes categorías de dolor en el pecho, lo que permite explorar su relación con el diagnóstico de enfermedades cardíacas.  
 **Presión Arterial en Reposo (trestbps):** Se registra la presión arterial en reposo de los pacientes, medida en mm Hg.  
 **Colesterol Sérico (chol):** Se registra el nivel de colesterol sérico en la sangre de los pacientes.  
 **Glucosa en Ayunas (fbs):** Se indica si el paciente tiene un nivel de glucosa en ayunas mayor a 120 mg/dl.  
 **Diagnóstico (num):** Esta variable registra si se ha diagnosticado una enfermedad cardíaca con un estrechamiento del diámetro de al menos el 50%, representado como un valor binario (1 para presencia de la enfermedad, 0 para ausencia).

Especificar datos
-----------------

   Chest Pain Type (tipo de dalor en el pecho)  1:Typical Angina 2:Atypical Angina 3:Non-Anginal Pain 4:Asymptomatic 

    fasting blood sugar &gt;120 mg/dl  1: &gt;120 mg/dl 0:  

    Genre(Género)  0:Mujer  1:Varón  

   Diagnosis of heart disease with 50% diameter narrowing  0:  1: &gt;50% diameter narrowing  


Fórmulas aplicadas
------------------

 ![formulas aplicadas](https://iili.io/HDnYVNs.jpg)
 
 Hallazgos y respuestas
----------------------

### ¿Cuál es la taza de diagnóstico de enfermedades?

 Entre los 303 pacientes analizados el 45.9% fue diagnósticado con problemas cardiacos, siendo los varones más propensos a sufrirlos.

 ![pregunta1](https://iili.io/HDnYQUP.jpg)
 
 ### ¿Quiénes tienen más de un 50% de estrechamiento y qué implica?

 Más del 50% de los hombres tienen &gt; 50% de estrechamiento del diámetro, esto significa que una arteria coronaria o una arteria que suministra sangre al corazón presenta un estrechamiento o reducción del diámetro mayor al 50%. Cuando el estrechamiento del diámetro de una arteria coronaria supera el 50%, existe un riesgo mayor de reducción del suministro de oxígeno y nutrientes al músculo cardíaco. Esto puede llevar a síntomas como angina de pecho (dolor en el pecho) durante el esfuerzo físico o el estrés emocional. Además, un estrechamiento severo también aumenta el riesgo de sufrir un ataque al corazón (infarto de miocardio), ya que la arteria estrechada podría bloquearse por completo debido a la ruptura de la placa acumulada.

 ![pregunta2](https://iili.io/HDnYbOg.jpg)
 
 ### ¿Qué consecuencias trae un estrechamiento mayor a al 50%?

 Una presión arterial alta, siendo el de las mujeres 146 en promedio y de los hombres 131, además el colesterol sérico puede alcanzar hasta un 276 en el caso de las mujeres y un 246 en el caso de los hombres, cabe resaltar que que la frecuencia cardiaca también disminuye hasta un 138.

 ![pregunta3](https://iili.io/HDnYyzJ.jpg)
 
 Conclusiones y recomendaciones
------------------------------

 En conjunto, estos hallazgos sugieren que los hombres con más del 50% de estrechamiento del diámetro en las arterias coronarias enfrentan un riesgo considerable de problemas cardiovasculares. Además, los niveles elevados de presión arterial, colesterol sérico y la disminución de la frecuencia cardíaca pueden agravar el riesgo y aumentar las posibilidades de desarrollar enfermedades cardíacas. Es crucial que las personas con estos factores de riesgo sean evaluadas por profesionales de la salud y reciban un tratamiento adecuado para reducir el riesgo de complicaciones cardiovasculares graves. Estos resultados subrayan la importancia de la prevención y el manejo adecuado de los factores de riesgo cardiovascular.

Dashboard
---------

 ![dashboard](https://iili.io/HDnaG1V.jpg)