# app-zapatos

dentro del proyecto nos encontraremos con dos carpetas, la de laravel y la de react, donde la primera funciona como el fronted y la segunda como el backend

por lo que descargamos el proyecto en nuesto htdocs, arrastramos esa carpeta a nuestro visual studio code
y accedemos con la terminal de visual a nuestra api
> cd api 

y en otra terminal dentro del mismo proyecto accedemos a react
> cd zapatos-frontes

Tambien necesitamos de vite, por lo que si hay algun problema solo usamos
> npm install

ahora comenzamos nuestro xampp con mysql y apache, y enviamos las migraciones, para despues en la terminal de laravel ejecutamos el comando serve y en la terminal de
react la de run
```
php artisan migrate
php artisan serve
npm run dev
```
Podemos crear nuestra base de datos por nuestra cuenta verificando el nombre en nuestro archivo env, o cuando realicemos la migracion.
En el link que nos deja react con vite accedemos a nuestra app, donde podremos usar nuestro proyecto con imagenes con urls estaticas
