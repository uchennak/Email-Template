# Email-Template

## Introduction
In this project, I created a Full-Stack email template web application. The goal is for the user to create email templates that they can reuse for later. This is useful for those who send repetitive emails that maintain the same structure, with only 1 few words swapped out.

## Technologies Used
* Python/Django
* HTML/CSS
* AWS RDS MySQL
* AWS App Runner
* AWS Parameter Store
* AWS CLI
* AWS Security Groups

The backed code is written using the Python language using the Django framework. This stack was chosen due to the minimized boilerplate code. 
The database used is AWS RDS MySQL. This is an AWS managed version of MySQL that takes care of certain responsibilities such as patching, backups, and replication.
The application is deployed using App Runner. 
Parameter store is used to store the the database credentials locally
