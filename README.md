# compunube

Accede a las bases de datos:
- PostgreSQL
  Host: localhost
  Puerto: 5432
  Usuario: myuser
  Contraseña: mypassword
  Base de datos: mydatabase

- MySQL
  Host: localhost
  Puerto: 3306
  Usuario: myuser
  Contraseña: mypassword
  Base de datos: mydatabase


Estructura del Proyecto

docker-compose.yml
README.md
-postgres-service/
  Dockerfile
  init.sql
- mysql-service/
  Dockerfile
  init.sql
- web-service/
  Dockerfile
  requirements.txt
  app.py

DEscoprimir la caprta y ejecutar el comado docker-compose up -d dentro de la carpeta demo-DB 
para validar las tablas  se debe navgar desde consola con curl http://localhost:5000/users y para customers http://localhost:5000/customers

mostarar los datos crados en las tablas,
