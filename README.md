<b> About </b>

This laravel project is using modular architecture. The purpose of this project is to ease the process of upscaling.

Generate your first module using <code> php artisan module:make Blog </code>. The following structure will be generated.

Modules/
  ├── Blog/
      ├── Config/
      ├── Console/
      ├── Database/
          ├── factories/
          ├── Migrations/
          ├── Seeders/
      ├── Entities/
      ├── Http/
          ├── Controllers/
          ├── Middleware/
          ├── Requests/
      ├── Providers/
          ├── BlogServiceProvider.php
          ├── RouteServiceProvider.php
      ├── Resources/
          ├── assets/
          ├── lang/
          ├── views/
      ├── Routes/
          ├── api.php
          ├── web.php
      ├── Tests/
      ├── composer.json
      ├── module.json
      ├── package.json
      ├── webpack.mix.js
