# SymphArt

> A basic Symfony 4 CRUD application used in the tutorial series "Up & Running With Symfony 4"

## 1. https://getcomposer.org/download/

## 2. https://www.apachefriends.org/index.html or http://www.wampserver.com/en/

## 3. Local Disk (C:) > xampp > htdocs
open with Git Bash

## 4. Check if composer is installed correctly
in git bash: 
```
composer
```
## 5. Create project
```
composer create-project symfony/skeleton symphart
```
## 6. Create a virtual host
Local Disk (C:) > xampp > apache > conf > extra > httpd-vhosts.conf
```
<VirtualHost *:80>
    DocumentRoot "C:/xampp/htdocs/symphart/public"
    ServerName symphart.test
</VirtualHost>
```

## 7. Open Notepad as admin  
Local Disk (C:) > Windows > System32 > drivers > etc

Show all files and open hosts
Add 
```
127.0.0.1 symphart.test
```
and save

## 8. Restart apache

## 9. In Git Bash
```
cd symphart
code .
```

Opens Visual Studio

## App Info

### Author

Brad Traversy
[Traversy Media](http://www.traversymedia.com)

### Version

1.0.0

### License

This project is licensed under the MIT License
