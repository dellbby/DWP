# DWP - Delia Akbari

## IP Address | Link
[http://162.243.247.121/](http://162.243.247.121/) - Production Server
[http://162.243.9.216/] (http://162.243.9.216/) - Staging Server

## Deployment Plan:
1. Create a Server

2. Login to Server and create new user other than root
  * add user “username”
  * create new password for username

3. Update/Upgrade all packages
  * sudo apt-get upgrade
  * sudo apt-get update 
  * sudo aptitude safe-upgrade
  * sudo reboot

4. Install Apache
  * sudo apt-get install apache2

5. Install Git
  * sudo apt-get install git-core

6. Connect git account with local and staging server

7. Create static website

8. Push files onto git repo through terminal as needed
