# symfony-react-project

This is a very simple test project based on React and Symfony.

## test guide

- make a test database(MYSQL)

  eg: db_name: symfony-react

- update .env file of backend

  DATABASE_URL="mysql://{username}{:password}@127.0.0.1:3306/{dbName}"

- run under the backend folder

  composer install

  php bin/console migrate

  php bin/console server:run

- run under the frontend folder

  npm install

  npm run start
