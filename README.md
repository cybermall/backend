# Tech Ecommerce Platform

A full-stack CRUD Laravel and ReactJs E-Commerce platform with a secure authentication system using Laravel Sanctum, with the admin dashboard.

## Getting Started

1. Clone the repo: `git clone https://github.com/itsmar1/tech-ecommerce.git`
2. cd to `server` folder, create and fill in `.env` file. See `.env.example`
3. Set your MySQL Databse keys
4. Set your Amazon S3 keys
3. Migrate db: `php artisan migrate`
5. Install frontend dependencies: `cd client && npm install`
6. Open up two command prompts. In one, run `php artisan serve` to start your backend server, in the other prompt run `npm start` to start the front end.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


### Prerequisites

* **TECHSHOP** backend uses [Composer](https://getcomposer.org) to manage its dependencies. So, before using it, make sure you have Composer installed on your machine.
* [Node.js](https://nodejs.org) needs to be installed on your computer to manage the frontend dependencies.
* Install [XAMPP](https://www.apachefriends.org/index.html) on your PC, launch the Xampp Control Panel, click on the Apache and MySql start buttons. Open a browser, copy and paste the url `http://localhost/dashboard/` then click on the phpMyAdmin tab. You should see the phpMyAdmin panel, click on the database tab in order to create a new database.


## Tech Stack

* [Laravel](https://laravel.com/docs/8.x/) - The backend php framework used
* [React](https://reactjs.org/) - The frontend framework used
* [Redux](https://react-redux.js.org/) - State management
* [Laravel Sanctum](https://laravel.com/docs/8.x/sanctum) - Authentication system
* [Tailwind](https://tailwindcss.com/) - CSS framework
* [MySQL](https://www.mysql.com/) - Database
* [Amazon S3](https://aws.amazon.com/s3/) - Object storage

## Live Demo
* Admin => email: `admin@techshop.com` | password: admin
* Client => email: `client@techshop.com` | password: client

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details