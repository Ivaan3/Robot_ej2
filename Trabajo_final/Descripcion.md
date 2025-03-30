1. Descripción del Proyecto (Ejercicio n° 3)

Este proyecto consiste en la creación de un robot que recopila archivos y los almacena dentro de una nueva carpeta creada, renombrándolos para asi mantener un orden y distinguir unos de otros. Además, los almacena junto a su archivo .md como documentación.

2. Frecuencia de ejecución 

El robot se ejecutara de forma manual.

3. Estructura del Archivo .ini

El archivo .ini contiene las configuraciones necesarias para el robot como rutas necesarias para obtener los archivos, guardarlos y crear un archivo .zip y configuración del correo como destinatarios, asunto, mensaje.

4. Flujo de Trabajo del Robot

El flujo de trabajo se puede dividir en los siguientes pasos:
	-Leer archivo de configuración (.ini)
	-Ejecutar el robot encargado de crear la carpeta de destino.
	-Ejecutar el robot encargado de buscar los archivos y almacenarlos en la carpeta de destino.
	-Ejecutar el robot encargado de crear un archivo .zip para poder enviarlos por correo
	-Enviar el correo a los destinatarios
	

5. Conclusión
Este robot permite automatizar el envío de emails con archivos determinados, permitiendo la reutilizacion de los robots hijos en futuros proyectos. El uso del archivo .ini proporciona flexibilidad, permitiendo cambiar configuraciones sin modificar el código del robot.

