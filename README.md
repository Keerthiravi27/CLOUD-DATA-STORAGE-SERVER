# CLOUD-DATA-STORAGE-SERVER
CLOUD DATA STORAGE SERVER

REG NO : 212224040156

NAME : Keerthana R

# AIM:
To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

# ALGORITHM

Log in to the AWS Management Console.

Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.

Create a DB Subnet Group with subnets in two Availability Zones.

Launch an Amazon RDS MySQL Multi-AZ DB instance.

Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.

Open the provided web application using the Web Server IP.

Enter the RDS endpoint, database name, username, and password.

Connect the application to the database.

Test the application by adding, editing, viewing, and deleting records.

# OUTPUT
<img width="1880" height="907" alt="image" src="https://github.com/user-attachments/assets/0e029456-1f86-4d6c-89f0-d9d4c8fe4345" />

<img width="1886" height="922" alt="image" src="https://github.com/user-attachments/assets/be8b7700-9a1b-4126-914f-ccfb3ca609c1" />

<img width="1887" height="925" alt="image" src="https://github.com/user-attachments/assets/4e293b95-d662-4f82-9b29-d1b8856e4ef6" />

<img width="1451" height="572" alt="image" src="https://github.com/user-attachments/assets/ddecc9d5-7928-4b48-8d62-91571bca666f" />

<img width="1811" height="880" alt="image" src="https://github.com/user-attachments/assets/c7a98a53-8d98-46f9-9756-f4536c775e52" />

<img width="1495" height="910" alt="image" src="https://github.com/user-attachments/assets/36cbed86-e8db-4072-8c4f-583f1d39b6a4" />

# RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.

