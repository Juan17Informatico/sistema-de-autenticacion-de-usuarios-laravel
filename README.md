# Proyecto Laravel 11 con Breeze y Blade

## Instalación

1. Clonar el repositorio:
   ```sh
   git clone https://github.com/tu-repo.git
   cd mi-proyecto
   ```
2. Instalar dependencias:
    ```sh
    composer install
    npm install
    npm run dev
    ```
3. Configurar .env y generar clave:
    ```sh
    cp .env.example .env
    php artisan key:generate
    ```
4. Configurar base de datos en .env y ejecutar migraciones:
    ```sh
    php artisan migrate
    ```
5. Levantar el servidor:
    ```sh
    php artisan serve
    ```

## Funcionalidades
- ✅ Registro e inicio de sesión con Breeze
- ✅ Soporte para Blade y modo oscuro
- ✅ Recuperación de contraseña
- ✅ Middleware de autenticación
- ✅ Pruebas con PHPUnit