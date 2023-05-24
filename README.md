# Herramienta-Administracion-CASOS-DE-USO

Herramienta en Excel basada en la desarrollada por la comunidad financiera holandesa MaGMa para la gestión y administración de casos de uso SIEM.

Usar herramienta de control y visibilidad de Casos de Uso

La herramienta fue modificada y actualizada, ajustada de acuerdo con el macro MITRE ATT&CK para el proyecto de grado de la especialización de ciberseguridad de la Universidad Catolica de Manizales (UCM)

El uso de la herramienta permitirá a las organizaciones tener la capacidad de control y monitoreo de seguridad basada en las necesidades de detección de amenazas emergentes y las necesidades de cumplimiento.


Para usar la herramienta se debe seguir los siguientes pasos:

Diligencie la información en la pestaña DRIVERS

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/622d5546-e4a7-4f60-86ac-73a03ed218fd)


En esta tabla se debe listar todos los drivers de negocio y los drivers de cumplimiento de la compañía. Estos son los factores que impulsan la necesidad de proteger la información de la organización. Son la base en la definición de los casos de uso.
Esta información hace parte de la recolectada en la metodología propuesta en los puntos iniciales.


En la Pestaña Tácticas recomendamos incluir todas las tácticas de la Matriz de MITRE ATT&CK y otras amenazas propias del segmento de la organización. 
Asigne un identificador de dos letras único, que permita identificar la táctica.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/a539f520-167b-4884-9d68-4cae9ad8a5fd)

En la pestaña Técnicas, recomendamos listas cada una de las técnicas usadas por cada una de las tácticas de MITRE ATT&CK y las técnicas usadas de las otras amenazas.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/74c17fdf-093c-443c-9881-c4fb30da8469)


Al igual que el identificador de la táctica, en la pestaña Nivel 2 Caso de Uso, debe crear un identificador de la técnica asociada a la táctica. Para este caso debe usar las dos primeras letras de la táctica y luego tres letras que identifiquen la técnica separada por un guion como se muestra en la siguiente tabla

En la pestaña Reglas, ingrese todos los nombres de las reglas de correlación que tienen implementadas en la actualidad.
Importante que las reglas cuenten con una estandarización para que la herramienta pueda contabilizar y generar graficas de uso por cada tácticas y técnica.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/fd8bfebe-55df-445c-bf1b-305f18af6e25)

En la columna H de la pestaña Tácticas, podrán ver la cantidad de reglas asociadas a cada táctica.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/af42b062-6200-411a-9892-9a9998136f73)


En la pestaña “Referencias”, agreguen detalle sobre:

Los actores maliciosos identificados 




Soluciones de Detección de la Organización 

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/f3220240-2337-4dbf-9078-1a9d266f0557)


En la pestaña “Reglas” encuentran las columnas con las métricas “Efectividad”, Implementación “Cobertura” , “Peso” y “Potencial”
![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/2985dd25-4c47-4f31-8af2-0468a9bcf7e5)

Efectividad:  Esta métrica se utiliza para determinar la efectividad del mecanismo de detección de la regla.
Implementación: Esta métrica se utiliza para determinar el nivel en el que se implementa el mecanismo de detección de la regla 
Cobertura: Esta métrica se utiliza para determinar el nivel en el que el mecanismo de detección la regla cubre el caso de uso
Peso: Esta métrica es un puntaje general calculado de efectividad, implementación y cobertura
Potencial: Esta métrica es un valor calculado que indica cuánta mejora se puede lograr al invertir en cobertura e implementación.

En la parte inferior de la pestaña “Tácticas” podrán ver un resumen del Rendimiento Global con algunas graficas de ejemplo. Estas pueden ser ajustadas y creadas a necesidad.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/f10e91fe-b4c9-4f8c-b9e4-fc2b87f6085d)
k







