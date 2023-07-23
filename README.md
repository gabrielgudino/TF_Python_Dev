# Automatización del traspaso de datos de una instancia SQL a BigQuery

> **Módulo 2: Python Data Engineer**

<p align="center">
  <img src="https://softr-prod.imgix.net/applications/b5cdb0d1-ba69-48f8-961f-8a89c9e7b1fd/assets/33448eb3-f23f-4e71-a164-872d3ec70526.png" alt="Módulo 2: Python Data Engineer | Datapath">
</p>

> Las respuestas a la ejercitación se encuentran en el notebook **"proyecto_funciones.ipynb"**

## Descripción general: 
La tarea consiste en desarrollar una solución automatizada que permita el traspaso de 
datos desde una instancia SQL hacia BigQuery. La solución debe incluir las funciones 
necesarias para realizar esta operación. El estudiante debe usar las mejores prácticas 
de desarrollo de software y considerar las consideraciones de rendimiento y seguridad. 
 
## Organización: 
Este proyecto se llevará a cabo de forma individual. Cada estudiante será responsable 
de diseñar, implementar y probar su propia solución. 
 
## Detalles del proyecto: 
El sistema requerido deberá contar con las siguientes funcionalidades: 
1. Función de conexión a la base de datos SQL: Esta función aceptará como 
entrada los parámetros de la base de datos (nombre de la base de datos, host, 
nombre de usuario, contraseña) para establecer una conexión segura utilizando 
una biblioteca de conexión a SQL. Si la conexión es exitosa devuelve un objeto 
de conexión; en caso de error, proporciona mensajes de error detallados. 
También puede gestionar la persistencia de la conexión según sea necesario. 
 
2. Función para enumerar todas las tablas en la base de datos SQL: Esta 
función recuperará y enlistará todas las tablas presentes en la base de datos 
SQL. 
 
3. Función para copiar tablas desde SQL a BigQuery: Esta función permitirá la 
copia de todas las tablas desde la base de datos SQL a BigQuery. Sin embargo, 
también ofrecerá la flexibilidad de seleccionar y copiar una tabla específica si el 
usuario así lo desea. 

## Extra Points:
Adicionalmente, los estudiantes pueden optar por desarrollar las siguientes 
características para obtener puntos adicionales: 
• Implementar la solución en Cloud Functions y/o Cloud Run. 
• Crear una interfaz de usuario para facilitar el uso de las funciones. 
• Implementar la solución en un contenedor Docker. 
• Incluir un manejo de errores robusto. 
 
## Criterios de evaluación: 
Los proyectos serán evaluados de acuerdo con los siguientes criterios: 
1. Funcionalidad: ¿La solución realiza las operaciones requeridas correctamente? 
2. Diseño de código: ¿El código está bien organizado y es fácil de entender? 
3. Uso de tecnologías adicionales: ¿El estudiante implementó características 
adicionales para obtener puntos extra? 
4. Documentación: ¿El estudiante incluyó comentarios en el código y 
documentación explicando cómo usar su solución? 
 
## Fecha de entrega: 
El proyecto debe ser entregado antes del Domingo 23 de Julio. 
 
## Forma de entrega: 
• Incluir todos los puntos solicitados en un artículo de Medium.
• Los estudiantes deben subir su proyecto a un repositorio en GitHub.


NOTA 1: Cambiar el archivo .env.template a .env y completar con las credenciales

NOTA 2: Copiar el archivo .json necesario para acceder a BigQuery