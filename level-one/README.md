# This is a tutorial series aimed at anyone wishing to get started with Developing using the PHP Framework Laravel

### Phase 1: The Setup

#### Code Editing

To get started, you are going to need a few tools, lets start with the code editor, my personal favourite is VSCode (Visual Studio Code) you can download it here https://code.visualstudio.com/download

#### Basics About PHP

This series does not require any prior knowledge about php, but its always a good place to start to at least know what the language is about, so to clarify a few confusions.

and by so doing, go ahead an make this link your bible and playground "https://www.w3schools.com/php/default.asp"

#### Basics About MySql

Similar to what i just mentioned redarding prior knowledge on php, the same goes for databases, and the most common Database Management System (DBMS) is MySql, which is Open Source meaning its completely free.

this link should help: "https://www.w3schools.com/sql/default.asp"

#### Installing PHP and MySQL

The easiest way to get these with one stone, is to simply install XAMPP (https://www.apachefriends.org/xampp-files/7.1.26/xampp-windows-x64-7.1.26-0-VC14-installer.exe) which is a LAMP (https://en.wikipedia.org/wiki/LAMP), where you can get these required softwares.

After installing XAMPP you can start jaming just to get a feel of how things work

You can now go ahead and run your XAMP installation and click Start on MySQL and Apache, once those are green and running you can go ahead to your browser and enter http://localhost:8080 you should be seeing a page with familiar information, if not check if your XAMPP services are running correctly and that they are green, not red

Checkout this tutorial: https://blog.udemy.com/xampp-tutorial

### Phase 2: The Playground

We will now test whether XAMPP has installed PHP successfully. To do this, fire up VSCode and type the following into a new document:

``` php
<?php
   echo ‘Hello world’;
?>
```
Save this file as ‘test.php’ in c:\xampp\htdocs\ (or whichever directory you installed XAMPP in).

Next: Navigate to localhost/test.php. You should see the “Hello World” message
