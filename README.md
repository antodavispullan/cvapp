cvapp
=====
OS: Ubuntu 14.10.

1. Installing Composer Globally

    [To download the composer package]  
    i.   /var/www$  curl -sS https://getcomposer.org/installer | php

    [To move the composer.phar file to the bin directory]            
    ii.  /var/www$  sudo mv composer.phar /usr/local/bin/
    
    [To set permission to the bin directory]                           
    iii. cd /usr/local$  chmod -R 777 bin
    
    [To verify composer is successfully working]                                 
    [shows Composer logo and version and certain commands]                           
    iv. cd /var/www$ composer.phar
    
    [To put this folder on the PATH environment variable type]                   
    v. /var/www$  export PATH="$PATH:~/.composer/vendor/bin"
    
    
    vi. /var/www$  echo $PATH

2. Installing Laravel 5.0

    [To download and install laravel]
    i.   /var/www$ sudo composer.phar create-project laravel/laravel <yourappdirectoryname> dev-develop --prefer-dist
    
    [To set Permission to the <yourappdirectoryname>]
    ii. /var/www$ sudo chmod -R 777 laravel
     

A cv with bootstrap frontend and api backend. The backend api may be in laravel or in codeigniter.
Based on well defined architecture
