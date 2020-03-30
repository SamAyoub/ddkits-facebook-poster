# DDKits Facebook Page/Group Poster

By Sam Elayyoub

### 1: Install Laravel 5.x

### 2: Composer require ddkits/ddkitsfacebook

### 3: Add DDkits within the service provider

    - ...
    'providers' => [
        /*
         * Application Service Providers...
         */
         ...
        Ddkits\Ddkitsfacebook\DdkitsfacebookServicesProvider::class,
    ],

### 4: In case of changing the theme

    - php artisan vendor:publish --tag="Ddkits\Ddkitsfacebook\DdkitsfacebookServiceProvider"

Done!!!