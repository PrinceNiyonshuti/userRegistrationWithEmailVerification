<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>


## About - User Registration

A typical user registration must be implemented. After entering the most important form data (firstname, lastname, email, password) and their successful validation, an
email with a confirmation link should be sent to the user. Optionally you can add address information about the user who registered.


## 1. Problems and findings

### Problems

- tried to use gmail and some case it was not working

### Findings

- Use of breeze and its functions
- Email verification
- Sending email

## 2. Time Taken to Complete

- The project took 40 minutes

## 3. Coding style and standards

- the coding style is used was line coding and error control , and the standard of using safe ,secure and portable codes

## 4. Source code files

[Link To Repository](https://github.com/PrinceNiyonshuti/userRegistrationWithEmailVerification.git)

[Link To Deployed App]()

## 5. Documentation

before starting to run the project , make sure you have mailtrap account in order to check the verification link

### Requiments
- Mailtrap [https://mailtrap.io/]
- create your .env file 
- create your database
### .env Mailtrap corresponding data

    MAIL_MAILER=
    MAIL_HOST=
    MAIL_PORT=
    MAIL_USERNAME=
    MAIL_PASSWORD=
    MAIL_ENCRYPTION=
    MAIL_FROM_ADDRESS=

### after run these script 
    php artisan migrate
    php artisan serve
