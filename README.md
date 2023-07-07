# POS-Laravel

## Description
POS-Laravel is a Point of Sale (POS) system developed as the final project for ELEC101. It is built using the Laravel framework and provides a user-friendly interface for managing sales, inventory, and customer data.

## Installation

### Prerequisites
- PHP (version X.X.X)
- Composer (version X.X.X)

### Steps
1. Clone the repository to your local machine:
   ```shell
   git clone https://github.com/your-username/POS-Laravel.git

  1. Navigate to the project directory:
      cd POS-Laravel
   
  2. Install the dependencies using Composer:
     composer install / composer update

  3. Create a copy of the .env.example file and rename it to .env:
     cp .env.example .env

  4. Generate an application key:
     php artisan key:generate

  5. Configure the database settings in the .env file:
      the database name  is  laravelpos

  6. Run the database migrations:
      php artisan migrate

  7. Start the development server:
      php artisan serve


License
This project is licensed under the MIT License.


