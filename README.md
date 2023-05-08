*Actividad de participacion 9*

Hecho por: John Sebastian Villegas Lopez

Se te ha proporcionado un archivo de texto que contiene registros de eventos en una red de servidores. Cada registro tiene el siguiente formato:

Fecha: <fecha>
Hora: <hora>
Servidor: <nombre_servidor>
Tipo de evento: <tipo_evento>
Descripción: <descripción_evento>
Tu tarea es leer el archivo y procesar la información para generar un informe que contenga las siguientes estadísticas:

Número total de eventos registrados.
Número de eventos por tipo.
Número de eventos por servidor.
Para resolver este problema, puedes crear una clase llamada AnalizadorEventos que tenga los siguientes métodos:

__init__(self, nombre_archivo: str) que reciba el nombre del archivo a procesar y lo guarde en un atributo de la clase.
procesar_eventos(self) -> Dict[str, Any] que lea el archivo de texto, procese los datos y devuelva un diccionario con las estadísticas calculadas.
A continuación, te dejo algunos tips para resolver este ejercicio:

Puedes utilizar la función open para abrir el archivo y leer los datos línea por línea.
Para llevar un registro de los eventos por tipo y por servidor, puedes utilizar un diccionario. La clave del diccionario sería el tipo de evento o el nombre del servidor, y el valor sería el número de eventos registrados.

