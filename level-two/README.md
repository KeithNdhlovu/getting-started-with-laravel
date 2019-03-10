# Installing Laravel

Laravel framework needs few requirements for getting installed on your system. A virtual machine has fulfilled each of these system requirements, Laravel's Homestead, hence it is a must to implement Homestead as the Laravel development environment for your local system.

Moreover, in case you do not use this virtual machine, the following requirements must be fulfilled:

PHP having version 7.0 or upper version
An OpenSSL Extension for PHP
A PDO Extension for PHP
Mbstring Extension for PHP
Tokenizer Extension for PHP
XML Extension for PHP

Laravel implements composer for managing dependencies within it. Hence, before use of Laravel, it needs to check whether you have composer setup on your system or not.

If you don't have composer installed on your computer, first visit this URL to download composer:

https://getcomposer.org/download/

When you are done installing the composer, cross-check whether it is installed or not, by typing in the command prompt the composer command. You can see the Composer screen in that CMD only.

It needs to be kept in mind to put the composer's system-wide vendor in bin directory within your $PATH; as a result, your system can locate the executable of laravel. Depending on which operating system you are using, this directory will exist. Still, for PCs having OS like MAC and Linux, it will be:

```
macOS: $HOME/.composer/vendor/bin
Linux OS: $HOME/.config/composer/vendor/bin
```

First of all, you have to download the installer of Laravel with the help of Composer, like this:

```
composer global require "laravel/installer"
```

When the installation is done, new command of laravel will start a new fresh installation in that directory you provide.

laravel new nirectory_name
The next thing you have to do is make a new folder in some specific path within your system, for keeping your Laravel projects. Move to that location where the directory is created. For installing the Laravel, the following command you have to type:

composer create-project laravel/laravel - prefer -dist
The command mentioned above will make Laravel installed on that specific directory. Type the next command:

php artisan serve
This above code will start Laravel service. A black screen will appear showing the message: Laravel Development server started on http://localhost:8080

Copy and paste: http://localhost:8080 in your browser, and you can see Laravel home screen appears in your browser.
