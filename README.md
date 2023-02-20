# Test Last Version Framework Laravel 10 
Desarrollo de una app de prueba de creación de comentarios y respuestas probando la última versión del Framework de PHP  **Laravel 10**

## Requerimiento de versiones
- Laravel: **10**

## Instalación App Laravel

Primero clonar este repositorio, instalar las dependencias y configurar tu archivo .env

```
git clone https://github.com/wilmertri/ProjectTestLaravel10.git
cd ProjectTestLaravel10
composer install
cp .env.example .env
```

Luego correr las migraciones y los seeders necesarios, se creara la base de datos

```
php artisan migrate --seed
```

## Instalación App JS

Ubicados en ProjectTestLaravel10

```
npm install
```

## Compilar y correr servidor NPM para desarrollo
```
npm run serve
```

## Ejecución Aplicación
```
php artisan serve
```

## Uso de Aplicación
Dar clic en el botón **Register** y registrar un usuario para usar la aplicación.
Ya con el usuario logueado puede crear comentarios y respuestas a dichos comentarios.