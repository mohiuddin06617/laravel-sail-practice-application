# Laravel Sail Basic Application

**Please follow below steps to run the application**. 

#### Step 1:
Clone the Laravel project repository to your local machine:

    git clone https://github.com/mohiuddin06617/laravel-sail-practice-application.git

#### Step 2:
Navigate to the project's root directory:

    cd laravel-sail-practice-application

#### Step 3:
Install project dependencies using Composer:

    composer install

#### Step 4:
Copy the .env.example file and rename it to .env:

    cp .env.example .env

#### Step 5:
Run the Sail installation command:

    ./vendor/bin/sail up
Otherwise to run in the background, please run below command :

    ./vendor/bin/sail up -d

#### Step 6:
After above command please run below command:

    ./vendor/bin/sail artisan migrate
