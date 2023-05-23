# Herramienta-Administracion-CASOS-DE-USO

Herramienta en Excel basada en la desarrollada por la comunidad financiera holandesa MaGMa para la gestión y administración de casos de uso SIEM.

Usar herramienta de control y visibilidad de Casos de Uso

La herramienta fue modificada y actualizada, ajustada de acuerdo con el macro MITRE ATT&CK para el proyecto de grado de la especialización de ciberseguridad de la Universidad Catolica de Manizales (UCM)

El uso de la herramienta permitirá a las organizaciones tener la capacidad de control y monitoreo de seguridad basada en las necesidades de detección de amenazas emergentes y las necesidades de cumplimiento.


Para usar la herramienta se debe seguir los siguientes pasos:

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/edac608e-1fd4-4b8f-b303-2be82389911d)


En esta tabla se debe listar todos los drivers de negocio y los drivers de cumplimiento de la compañía. Estos son los factores que impulsan la necesidad de proteger la información de la organización. Son la base en la definición de los casos de uso.
Esta información hace parte de la recolectada en la metodología propuesta en los puntos iniciales.


En la Pestaña Tácticas recomendamos incluir todas las tácticas de la Matriz de MITRE ATT&CK y otras amenazas propias del segmento de la organización. 
Asigne un identificador de dos letras único, que permita identificar la táctica.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/75c842bc-7073-471f-8529-1306bd6e3b4c)

En la pestaña Técnicas, recomendamos listas cada una de las técnicas usadas por cada una de las tácticas de MITRE ATT&CK y las técnicas usadas de las otras amenazas.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/b6cdc55d-6093-4e4a-b765-ab85879664a9)

Al igual que el identificador de la táctica, en la pestaña Nivel 2 Caso de Uso, debe crear un identificador de la técnica asociada a la táctica. Para este caso debe usar las dos primeras letras de la táctica y luego tres letras que identifiquen la técnica separada por un guion como se muestra en la siguiente tabla

En la pestaña Reglas, ingrese todos los nombres de las reglas de correlación que tienen implementadas en la actualidad.
Importante que las reglas cuenten con una estandarización para que la herramienta pueda contabilizar y generar graficas de uso por cada tácticas y técnica.

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/a317c7c9-ea7c-45d9-92d8-fa6ba7955754)

En la columna H de la pestaña Tácticas, podrán ver la cantidad de reglas asociadas a cada táctica.
![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/68326bbe-17a8-43cd-9ec0-2c9ee9c0bcb5)

En la pestaña “Referencias”, agreguen detalle sobre:

Los actores maliciosos identificados 

![image](https://github.com/MigCHZ/Herramienta-Administracion-CASOS-DE-USO/assets/134456656/dd948737-dcee-4f6b-9adb-f4273967d78b)


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







