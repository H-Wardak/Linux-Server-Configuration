# Linux-Server-Configuration

This application provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

This is the same application of [project 4](https://github.com/H-Wardak/item-catalog) Item Catalog, but hosted in Amazon Lightsail host service.

## Access the Project?
**IP address**  
18.195.49.168  

**SSH Port**  
2200

**Web Application URL**  
AWS-Server: http://ec2-18-195-49-168.eu-central-1.compute.amazonaws.com

## Installed Packegs
- Update all currently installed packages, then upgrade  
``` sudo apt-get update ```  
``` sudo apt-get upgrade ```

- Install Apache  
``` sudo apt-get apache2 ```

- Install libapache2-mod-wsgi  
``` sudo apt-get install libapache2-mod-wsgi ```

- Install PostgreSQL  
``` sudo apt-get install postgresql ```

- Install git, mostly it's already installed  
``` sudo apt-get install git ```

- Install ntp  
``` sudo apt-get install ntp ```

- Install sqlalchemy  
``` sudo pip install sqlalchemy  ```

- Install flask  
``` sudo pip install flask  ```

- Install python-psycopg2  
``` sudo apt-get install python-psycopg2 ```

- Install oauth2  
``` sudo pip install oauth2client ```

- Install passlib  
``` sudo apt-get install python-passlib ```

- Install requests  
``` sudo install python-requests ```

## Configuration Summary
- Start a new Ubuntu Linux server instance on Amazon Lightsail.
- Update all currently installed packages.
- Change the SSH port from 22 to 2200. 
- Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
- Create a new user account named grader.
- Give grader the permission to sudo.
- Create an SSH key pair for grader using the ssh-keygen tool.
- Install and configure Apache to serve a Python mod_wsgi application.
- Install and configure PostgreSQL, and create a new database user named catalog 
- Configure Google+ Oauth URIs to reflect our Web APP URL






