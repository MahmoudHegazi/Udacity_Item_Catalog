![udacity logo](https://s3-us-west-1.amazonaws.com/udacity-content/rebrand/svg/logo.min.svg "Udacity")
# Item Catalog Web app - Udacity
### Full Stack Web Development ND
[Udacity.com](https://www.udacity.com)


_____________________

# About
REST Full app , can read and update and create and delete data from database, it has : Authentication &amp; Authorization Page implements a third-party authentication &amp; authorization service like Google Accounts instead of implementing its own authentication &amp; authorization spec.there a “login” and “logout” button/link in the website?

# Prerequisites
* Python: 3.8 https://www.python.org/downloads/release/python-380/  
* Vagrant: https://releases.hashicorp.com/vagrant/  
* VirtualBox: 3 
* Git : https://git-scm.com/downloads 

# Notes Before Using this App 
* You can search only By car name not the company name.
* this lastadded section show you Last added posts not lists in order to make it Like this below
* 128(Fiat).

## How To set up VM and use this app on windows:

We're using tools called Vagrant and VirtualBox to install and manage the VM. 
You'll need to install these to do some of the exercises. 
The instructions on this page will help you do this.

[Download This File](https://github.com/udacity/fullstack-nanodegree-vm)

1. Download virtualBox, vagrant, GitBash
2. install them 
3. access vagrant file that You have downloadead
4. type vagrant up [Enter] 'It Will take long time'
5. type vagrant ssh

## how to access vagrant file:
1.  unzip The file u have downloaded and put it in Downloads folder.
2.  open GitBash and type cd Downloads [Enter]
3.  then ls and copy the file name Then click paste or control [shift] + [insert]
4.  use cd on the file name fullstack-nanodegree-vm
5.  then cd vagrant , and run vagrant up and vagrant ssh


## Getting an error in Setup VM?
1.  install another VM Verssion
2.  try To Re-Install the vagrant and Virtualbox
3.  else Search google

# Database Tables :

## 1- Users  
#### Primary Key : id

id | name | email | picture
--- | --- | --- | ---
*integer* | `text` | **text** | **Text**



## 2- Car 
#### Primary Key : id, UNIQUE CONSTRAINT : user_id, foreign Key: Users
 
name | id  
--- | ---  
**Text** | **integer**


## 3- CarType 
#### Primary Key : id  UNIQUE CONSTRAINT : user_id,car_id, foreign Key: Users, Car

Name | Id | description | price | car_id | user_id
--- | --- | --- | --- | --- | --- 
 **text** | **inet** | **text** | **text** | **integer** | **integer**
 
 
# Features and Functions

1.   The project implements a JSON endpoint that serves the same information.
2.   Website reads category and item information from a database.
3.   Website includes a form allowing users to add new items and correctly processes submitted forms.
4.   Website include a form to edit/update a current record in the database table and correctly processes submitted forms.
5.   Website does include a function to delete a current record.
6.   Do create, delete, and update operations consider authorization status prior to execution
7.   Page implements a third-party Oauth2 service (Google Accounts) instead of implementing its own authentication & authorization spec.
8.   there is a 'Login' and 'Logout' button/link in the project. 
9.   neatly formatted and compliant with the Python PEP 8 style guide.
10.  comments present and effectively explain longer code procedures.
11.  full responsive.
12.  working searching Filed.
13.   Using some Python function to add some AI to the web app

# ScreenShoots
![screenshot1](app1.JPG "screenshot1")
![screenshot2](app2.JPG "screenshot2")
![screenshot3](app3.JPG "screenshot3")

   
## Author:
   ### Mahmoud Hegazy   
   ![author photo](https://avatars2.githubusercontent.com/u/55125302?s=96&v=4 "Author")
