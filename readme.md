# LMS-Laravel

- [About](#about)
- [License](#license)

### About
LMS-Laravel is a Learning Management System (or LMS) that facilitates the creation of educational content by allowing you to manage courses and learning modules. The platform is simple and intuitive and provides features for:
1. The Teacher (course creator)
2. The Student (or user)
3. The Admin

As the name suggests, LMS-laravel is built on the latest Laravel framework, and uses various open source packages.
This application is still in development, if you want to collaborate on the development, send us an email: 
```
Eng Hasan Hajjar: eng.hasan.hajjar@gmail.com
```

### Installation
* Run `git clone https://github.com/Eng-Hasan-Hajjar/LMS-Laravel-Learn-Management-System.git`
* `cd LMS-Laravel-Learn-Management-System` 
* Run `composer install` (install composer beforehand)
* From the projects root run `cp .env.example .env`
* Configure your `.env` file, with:

Database settings
```
DB_DATABASE=lms_laravel
DB_USERNAME=root
DB_PASSWORD=root
```


Email settings (using a provider like Mailgun, Amazon SES, etc)

* Run `php artisan key:generate`
* Run `php artisan migrate`
* For Auth API (to configure Laravel Passport), run: `php artisan passport:install`
* Run `npm install`
* Run `php artisan db:seed`

* Start the Laravel server `php artisan serve --port=8000`

* Start the Websocket server (for chat functionality) `php artisan websockets:serve`


### License
LMS-Laravel is licensed under the MIT license. Enjoy!

## Seeded Credentials

User: admin
Pass: admin123

## my logo
<div>
        <img src="حسن حجار.png">
</div>
