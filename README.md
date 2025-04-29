# TP-Proyecto-final-MariaChacon

Aplicación desarrollada en Laravel para gestionar equipos deportivos y sus jugadores.

## Requisitos

- PHP >= 8.1
- Composer
- Node.js y npm
- MySQL o PostgreSQL
- Laravel >= 10.x
- Docker (opcional)

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/usuario/proyecto_mariachacon.git
   cd proyecto_mariachacon
2. Instala dependencias de PHP:
   composer install

3. Configura el entorno:
cp .env.example .env
php artisan key:generate

4. Ejecuta las migraciones y seeders:
php artisan migrate --seed

5. Levanta el servidor:
php artisan serve
