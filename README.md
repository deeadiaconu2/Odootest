1. Crear repositorio en github
2. Crear  una carpeta de extra-addons
3. Dentro de extra-addons hay que crear 2 partes:
     -Crear carpeta de dummy_module:
       -Dentro de la carpeta creamos 2 archivos: __init__.py (que está vacio) y __manifest__.py (con código dentro)
     -Creamos tambien un archivo que se llama gitkeep (que está vacío)
4. Crear el archivo Dockerfile (con código dentro)
5. El código de Dockerfile se tiene que llamar igual en ambos lados
6. Crear un proyecto en render
7. Dentro del proyecto creamos dos servicios:
     -OdooInstalacion
     -Progress_db
8. Cuando se haya cargado ya le das a new posgress
9. Crear una base de datos y lo vinculas al proyecto
10. Dentro de progress_db hay que crear unas conexiones:
     -Hostname
     -Port
     -Database
     -Username
     -Password
11. Dentro de OdooInstalacion hay que darle a la parte de Enviroment y crear una serie de variables (que son las que están en progress_db):
     -PGDATABASE
     -PGHOST
     -PGPASSWORD
     -PGUSER
