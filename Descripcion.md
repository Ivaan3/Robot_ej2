1. Descripción del Proyecto (Ejercicio n° 2)

Este proyecto consiste en la creación de un robot que procesa un archivo Excel con información de clientes y su condición frente al IVA
(por ejemplo, "Responsable Inscripto", "Exento", "No Responsable", etc.). El robot toma esta información y discrimina a los clientes en
diferentes hojas dentro de un archivo Excel según su condición frente al IVA.

2. Frecuencia de ejecución 

El robot se ejecutara de forma manual.

3. Estructura del Archivo .ini

El archivo .ini contiene las configuraciones necesarias para el robot, como las condiciones de IVA y la ruta de los archivos de entrada y salida.

4. Flujo de Trabajo del Robot

El flujo de trabajo se puede dividir en los siguientes pasos:
	-Leer archivo de configuración (.ini)
	-Leer archivo Excel de entrada
	-Crear nuevo archivo de Excel a editar
	-Filtrar los datos según la condición frente al IVA en distintas hojas dentro del archivo mediante comandos de logica como grupo, for, elif
	-Guardar los datos
	-Creación de un log a modo de control como buena práctica

5. Conclusión
Este robot permite automatizar la clasificación de clientes según su condición frente al IVA, mejorando la eficiencia del proceso y evitando posibles
errores humanos. El uso del archivo .ini proporciona flexibilidad, permitiendo cambiar configuraciones sin modificar el código del robot.

Video de documentación
https://drive.google.com/file/d/16e77RTheFh1InjoCluub7I5NeEJMZ9pl/view?usp=drive_link