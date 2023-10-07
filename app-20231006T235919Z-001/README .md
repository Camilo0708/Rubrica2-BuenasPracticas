# Mi Proyecto Web de Tareas

Este es un proyecto simple de una lista de tareas desarrollado en Python utilizando el framework Flask y una base de datos Microsoft Access. Permite a los usuarios agregar, marcar como completadas y eliminar tareas.

## Requisitos

Antes de ejecutar este proyecto, asegúrate de tener instalado Python y las siguientes bibliotecas:

- Flask
- pyodbc

Puedes instalar estas bibliotecas utilizando pip:
pip install Flask pyodbc

## Configuración de la Base de Datos

Asegúrate de tener una base de datos Access (.accdb) y configura la conexión en el archivo `app.py` en la siguiente línea:

conn = pyodbc.connect(r'DRIVER={Microsoft Access Driver (*.mdb, *.accdb)};'
                      r'DBQ=C:\Users\Camilo\Downloads\app-20231006T235919Z-001\TasksDB.accdb;')

## Ejecucion
Para ejecutar la aplicación, simplemente ejecuta app.py. La aplicación se iniciará en modo de depuración y estará disponible en http://localhost:5000/.

## Uso
Visita la página principal para ver la lista de tareas disponibles.
Agrega nuevas tareas proporcionando una descripción en la página principal.
Marca tareas como completadas haciendo clic en el enlace correspondiente.
Elimina tareas haciendo clic en el enlace de eliminación.
¡Disfruta gestionando tus tareas con esta sencilla aplicación!
