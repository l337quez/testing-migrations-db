# testing-migrations-db
ejemplo para testiar una migracion de una base de datos no sql a sql. Es importante testear que todos los datos se hayan guardado bien


Inicializamos el proyecto asi

npx typeorm init --name testing_migrations_db --database postgres


instalamos dependencias
Si bien en el comando anterior agregamos a postgres, ahora debemos agregar a mongo. Entonces npm install para que se instales las dependencias del package.json

npm install

Luego instalamos el driver de Mongo
npm install mongodb




fuentes:
https://www.youtube.com/watch?v=yXkJRSC63eM
