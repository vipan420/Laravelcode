

# This Project Just Basic Implementation Of Passport In Laravel To Develop Rest Api 

## This Project Include Login,Register Basic Product Information 
 
   ## First Step
       Composer create-project laravel/laravel Myproject 5.8
   ## Second Step install package Passport
      composer require laravel/passport
   ## Now You Need to add this code into your config file 
      config/app.php
     'providers' =>[
                   Laravel\Passport\PassportServiceProvider::class,
                   ],
   ## Now run migration command to install 
      php artisan migrate
   ## Now install passport ot your laravel
      php artisan passport:install
   ## Now add 
      In model, you need to add HasApiTokens class of Passport,

      In AuthServiceProvider wich is app/Providers/AuthServiceProvider.php you need to add “Passport::routes()”,

      In auth.php, we added API auth configuration.

      app/User.php


##Postman Repo Url

  https://www.getpostman.com/collections/062eab3206c7bd47a621
      

 





