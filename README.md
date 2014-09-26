cvapp
=====
OS: Ubuntu 14.10.

1. Installing Composer Globally

    [To download the composer package]  
    i.   /var/www$  curl -sS https://getcomposer.org/installer | php

    [To move the composer.phar file to the bin directory]            
    ii.  /var/www$  sudo mv composer.phar /usr/local/bin/composer
    
    ----------********-------------
    via laravel installer
    sudo composer global require "laravel/installer=~1.1"
    
    export PATH="$PATH:~/.composer/vendor/bin"
    echo $PATH
    
    [To see the laravel commands]
    ~/.composer/vendor/bin/laravel
    
    [To see the laravel commands]
    laravel
    
    laravel new cvapp //ignore this
    
    cd cvapp          //ignore this
    
    php artisan -v    //ignore this
    
    cd ..
    
    [To install version 5]
    sudo composer create-project laravel/laravel cvapp dev-develop --prefer-dist
    
    cd cvapp
    php artisan -v
    
    cd ..
    sudo chmod -R 777 cvapp
    cd cvapp
    
    php artisan
    
    php artisan serve
    
    ----------********-------------
    
    
    [To set permission to the bin directory]                           
    iii. cd /usr/local$  chmod -R 777 bin
    
    [To verify composer is successfully working]                                 
    [shows Composer logo and version and certain commands]                           
    iv. cd /var/www$ composer.phar
    
    [To put this folder on the PATH environment variable type]                   
    v. /var/www$  export PATH="$PATH:~/.composer/vendor/bin"
    
    [To know what the PATH contains]                                  
    vi. /var/www$  echo $PATH

2. Installing Laravel 5.0

    [To download and install laravel]                              
    i.   /var/www$ sudo composer.phar create-project laravel/laravel yourappdirectoryname dev-develop --prefer-dist
    
    [To set Permission to the yourappdirectoryname]                          
    ii. /var/www$ sudo chmod -R 777 yourappdirectoryname
    
3. Viewing the project in the browser
     

A cv with bootstrap frontend and api backend. The backend api may be in laravel or in codeigniter.
Based on well defined architecture
