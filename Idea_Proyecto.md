Título del proyecto: "Generador de Datos de Prueba para Bases de Datos Relacionales"


1. Descripción del Proyecto:
Este proyecto nace como una solución a la necesidad de generar datos de prueba realistas y eficientes para bases de datos relacionales en entornos de desarrollo y prueba. Muchos desarrolladores enfrentan el problema de crear manualmente datos falsos, lo que es tedioso y propenso a errores. Además, los datos generados manualmente suelen ser inconsistentes y no reflejan casos reales. Con una aplicación web que automatiza este proceso utilizando el patrón MVC y JDBC, los desarrolladores pueden generar grandes volúmenes de datos realistas (como nombres, correos y teléfonos) de manera rápida y controlada, optimizando el tiempo de prueba y validación de sus aplicaciones sin comprometer la seguridad ni la privacidad.

Mediante una interfaz sencilla, el usuario puede especificar cuántos registros desea insertar en una tabla determinada (por ejemplo, clientes). La aplicación utiliza una librería de generación de datos falsos (faker) para crear información realista como nombres, correos electrónicos, teléfonos y ciudades. Estos datos son almacenados directamente en la base de datos mediante conexiones JDBC. Además, el proyecto está diseñado para reforzar el aprendizaje de buenas prácticas en Java web, separación de responsabilidades por capas, uso de librerías externas y manipulación de bases de datos desde el backend.


2. Objetivos del Proyecto
Objetivo General:
    - Desarrollar una aplicación web en Java que permita generar e insertar datos de prueba en una base de datos relacional de forma automatizada, utilizando la arquitectura de tres capas y el patrón MVC.

Objetivos Específicos:
    - Diseñar una interfaz web simple que permita al usuario ingresar la cantidad de registros a generar.
    - Aplicar el patrón MVC y arquitectura en tres capas (modelo, servicio y acceso a datos) para separar responsabilidades del sistema.
    - Implementar la conexión a base de datos mediante JDBC, asegurando una inserción eficiente y controlada de datos.
    - Utilizar la librería Faker para generar datos falsos con formato realista (nombres, correos, teléfonos, etc.).
    - Registrar los datos generados en una tabla específica dentro de una base de datos relacional (por ejemplo, MySQL).
    - Validar y mostrar mensajes al usuario sobre el resultado de la operación de generación.


Integrantes:
- Nestor Serrano Ibañez
- Junior Mamani Estaña
- Richard Podestá Condori
