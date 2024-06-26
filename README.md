<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Cara Install Boostrap di Laravel

Berikut ini langkah-langkah untuk instalasi Bootsrap di Laravel 10:

-     composer require laravel/ui
- tunggu instalasi selesai.
-     php artisan ui bootstrap
-     npm install
-     npm run build
- untuk compile namun bisa juga dijalankan di developer :
-     npm run dev
- pada halaman view blade.php tambahkan pada header :
-     @vite(['resources/sass/app.scss','resources/js/app.js']) 
- selesai.

Berikut ini langkah-langkah menambahkan bootstrap Icon di laravel:

-     npm install bootstrap-icons
- pada file : "resources/sass/app.scss" tambahkan kode berikut :
-     @import 'bootstrap-icons/font/bootstrap-icons.css';
- npm run dev --> atau --> npm run build
- selesai.
- berikut contoh icon :
  
        <i class="bi bi-bag-heart-fill"></i>
        <i class="bi bi-app"></i>
        <i class="bi bi-arrow-right-square-fill"></i>
        <i class="bi bi-bag-check-fill"></i>
        <i class="bi bi-calendar-plus-fill"></i>
        <i class="bi bi-airplane"></i>
        <i class="bi bi-bar-chart-fill"></i>
        <i class="bi bi-bell-fill"></i> 



namun untuk lebih jelas anda bisa mengunjungi dokumentasi laravel ui : (https://github.com/laravel/ui).

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
