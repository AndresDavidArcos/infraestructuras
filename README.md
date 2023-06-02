Para iniciar el proyecto se debe tener creada una base de datos llamada todo en postgresql.
Una vez hecho esto, se puede correr en el directorio raiz del proyecto los siguientes comandos:
- flask db init
- flask db migrate
- flask db upgrade
Estos comandos crearan las tablas necesarias en la base de datos.
Por ultimo se ejecute flask run.