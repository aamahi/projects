# Inventory Management

An inventory management web application. It is developed using PHP laravel framework. Each module of this project is independent reusable package. I used queue with redis for sending email, SMS and others time consuming task and passport package for API authentication. For frontend i used AngularJs. Broadcasting with pusher for sending notifications.

## Modueles of the porject

* HR
* Products
* Purchase / Receiving
* Sales / Deliver
* Investment
* Cash
* Bank
* Expenditure
* Reports


## Feature of Laravel used to develop this application

* Queue for sending email, SMS and others time consuming task
* Broadcasting with pusher for sending notifications.
* Redis for caching and Queue
* Event listener
* And many others common features ....

## Laravel packages used to develop this application

* "laravel/passport": For API Authentication
* "laracasts/flash": For Flash messaging
* "laravelcollective/html": For Form and html
* "nwidart/laravel-modules": For creating and mangeing module
* "unisharp/laravel-filemanager": To manage file and image uploading
* "predis/predis": For using Redis
* "pusher/pusher-php-server": For using pusher with broadcasing
* "barryvdh/laravel-cors": For API call without CSRF token