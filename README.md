# Pengembangan Sistem Informasi Kepegawaian di PT. Jordan Citra Niaga Kota Semarang dengan Menggunakan Framework Laravel 

## fitur
user 
- kelola data pribadi
- pengajuan presensi
- pengajuan cuti

admin
- kelola data karyawan
- kelola presensi
- kelola cuti

## tampilan
user 
![WhatsApp Image 2025-04-09 at 19 46 14_c82d0ea9](https://github.com/user-attachments/assets/9e648344-1840-4e45-8d14-1259dae5bd19)
![WhatsApp Image 2025-04-11 at 00 15 43_63c3b690](https://github.com/user-attachments/assets/1fb65123-1523-4f17-b641-8c8115b2b542)
![WhatsApp Image 2025-04-11 at 00 16 34_694518c7](https://github.com/user-attachments/assets/2d393b7d-74b8-44b7-a280-901571092573)
![WhatsApp Image 2025-04-11 at 00 16 43_06067272](https://github.com/user-attachments/assets/ef90dbe4-ca50-4358-866f-f01665d82858)




admin
![WhatsApp Image 2025-04-09 at 19 44 58_795b81bc](https://github.com/user-attachments/assets/e86303ac-40f8-4f22-a21e-188dfcf1dc6f)
![WhatsApp Image 2025-04-09 at 19 45 13_0811e876](https://github.com/user-attachments/assets/dd267dfe-693c-4eec-a645-936d978138bb)
![WhatsApp Image 2025-04-11 at 00 16 27_c20fe054](https://github.com/user-attachments/assets/1c464938-d3a9-4f97-bcef-b2cec6b1ce26)
![WhatsApp Image 2025-04-11 at 00 16 12_97be6869](https://github.com/user-attachments/assets/53473c95-dc77-40ff-b689-a0d8841075d3)
![WhatsApp Image 2025-04-11 at 00 15 32_ffc7ee50](https://github.com/user-attachments/assets/277d87ca-718b-41ce-ac1a-fe43a85ba651)


## how to install 
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>


## Installation and Setup

### Prerequisites
- PHP >= 7.3
- Composer
- Laravel >= 10.0
- Node.js & NPM

### Step 1: Clone the repository
```bash
git clone https://github.com/shintothemars/worksync.git
cd worksync
```

### Step 2: Install dependencies
```bash
composer install
npm install
```

### Step 3: Configure environment
Copy the `.env.example` file to `.env` and update the necessary environment variables.
```bash
cp .env.example .env
```

### Step 4: Generate application key
```bash
php artisan key:generate
```

### Step 5: Set up database connections
```bash
DB_DATABASE=worksync
DB_USERNAME=root
DB_PASSWORD=

```

### Step 6: migration and seeder
```bash
php artisan migrate --seed
php artisan migrate:fresh --seed
```

### Step 7: Create storage link

```bash
php artisan storage:link
```

### Step 8: Serve the application
```bash
php artisan serve
```

Visit `http://localhost:8000` in your browser to see the application running.

## Usage
- To access the Filament admin panel, navigate to `/admin` in your browser.
- Use the credentials you set up during the Filament installation to log in.

## Contributing
Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.



<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
