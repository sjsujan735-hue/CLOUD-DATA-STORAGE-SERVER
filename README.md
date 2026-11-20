# EX-5 CLOUD DATA STORAGE SERVER
# REG NO : 212225220108
# NAME : SUJAN S

## AIM

To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

## ALGORITHM

1. Log in to the AWS Management Console.
2. Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.
3. Create a DB Subnet Group with subnets in two Availability Zones.
4. Launch an Amazon RDS MySQL Multi-AZ DB instance.
5. Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.
6. Open the provided web application using the Web Server IP.
7. Enter the RDS endpoint, database name, username, and password.
8. Connect the application to the database.
9. Test the application by adding, editing, viewing, and deleting records.

## OUTPUT
<img width="1916" height="907" alt="Screenshot 2026-11-20 195501" src="https://github.com/user-attachments/assets/4d36711c-d4c2-47f9-b8bd-e52f436dc37b" />
<img width="1917" height="912" alt="Screenshot 2026-11-20 195526" src="https://github.com/user-attachments/assets/2c38b3d6-3a63-4301-927d-e5c7d3107b98" />
<img width="1911" height="902" alt="Screenshot 2026-11-20 195732" src="https://github.com/user-attachments/assets/e5bc8440-2f33-40c8-a8d7-59646dbbdabe" />
<img width="1917" height="917" alt="Screenshot 2026-11-20 201325" src="https://github.com/user-attachments/assets/c8c04aa7-61e8-4386-9959-7ce1dba3e97c" />
<img width="1917" height="913" alt="Screenshot 2026-11-20 202109" src="https://github.com/user-attachments/assets/13bdaf66-c980-4780-ba64-7cf01fa17c61" />
<img width="1917" height="930" alt="Screenshot 2026-11-20 202206" src="https://github.com/user-attachments/assets/4fd4ddc4-8e3d-4616-84c3-67c86ee98265" />
<img width="1807" height="847" alt="Screenshot 2026-11-20 202332" src="https://github.com/user-attachments/assets/abf7a46a-e251-4bf6-bb41-ae450edee175" />
<img width="1917" height="878" alt="Screenshot 2026-11-20 202401" src="https://github.com/user-attachments/assets/80c1e5e1-8ebb-447e-b951-86354766a733" />
<img width="1905" height="951" alt="Screenshot 2026-11-20 202524" src="https://github.com/user-attachments/assets/164e5815-e941-4198-b51b-a17d8829d54b" />




















## RESULT

The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
