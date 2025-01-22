MYSQL SERVER ON AWS EC2 INSTANCE
STEP1: create an ec2 intsance->then connect it then we will get command prompt like page(Choose ubuntu AMI)
Type the following commands
1. sudo apt udate
2. sudo apt install mysql-server(installing mysql)
3. sudo systemctl status mysql
4. sudo mysql(to login to mysql)
5. ALTER USER 'root'@'localhost' Identifed with mysql -native password BY 'kav@123'
6. CREATE DATABASE mysql-test;
7. USE mysql-test;
8. CREATE TABLE TABLE1(ID INT,NAME VARCHAR(45));
9. INSERT INTO TABLE1 VALUES(1,'KAVYA'),(2,'SRI');
10. SELECT * FROM TABLE1;
11. 
