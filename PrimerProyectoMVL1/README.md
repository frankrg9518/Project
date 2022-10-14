Este proyecto redirige a una página web que muestra varias vistas, templates y modelos. Este contenido 
es guardado en una base de datos
Las vistas provienen de la app del proyecto llamada AppCoder. Se encuentran en la carpeta views.py
Las vistas representan varias secciones de la página web, ademas están encargadas de redirigir a otras secciones de la página web
Estas vistas se pueden localizar o llamar usando el nombre asignado para cada una en el archivo de
urls.py
Los modelos permiten guardar datos en las bases de datos a través de objetos
Todos fueron definidos en el archivo models.py y se puede acceder a ellos desde la app de base de datos DB Browser y desde la herramienta de Django: admin
Algunos archivos html de la sección plantillas/AppCoder usan la característica de Herencia desde el archivo padre.html para usar características del template html que tiene este archivo
Este proyecto tiene archivos o formularios que permiten insertar datos a las clases de los modelos y también formularios que permiten buscar datos en la base de datos