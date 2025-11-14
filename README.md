# Data Migration using Amazon RDS (Iaas -> Paas)

## Project Overview 

In this mini project, we are moving a **datbase** from an **EC2 Instance (Iaas)** to **Amazon RDS (Paas)**. 

This shows how data can be easily shifted from a self-managed databse to a managed database service.

---
## Aim of project:

- To undestand the difference between Iaas and Paas 
- To learn how to miagrate data from Ec2 MySQL to RDS MySQL
- To see how RDS makes database management easier.
---
## Simple architecture
EC2 Instance (MySQL) 
 ----> Amazon RDS (MySQL)

              Iaas ----> Paas   

## Diagram

![](./img/WhatsApp%20Image%202025-11-14%20at%2015.08.06_2d0734b0.jpg)
---

## Steps to do the Project

### Step1:Create Amazon RDS (Paas)

1. Go to AWS Console --> RDS --> Allow 3306 port number to security group --> Create dabase named as Facebook.

![](./img/Screenshot%201.png)

### Step2: Create Database on Ec2 (Iaas)

1. Launch an temperory EC2 instance-

![](./img/Screenshot%202.png)

2. Take access of your EC2 instance-

![](./img/Screenshot%203.png)

3. Install and start mariadb105-server-

![](./img/Screenshot%204.png)

4. Go to mysql-

![](./img/Screenshot%205.png)

 5. create dabase named as facebook and create table and insert values into table-

![](./img/Screenshot%206.png)

### Step 3: Extract data from EC2 server and convert into file-

![](./img/Screenshot%207.png)

### Step 4: Migrate data from Ec2 to RDS and go to your RDS instance

![](./img/Screenshot%208.png)

### Step 6: Check data from Fackebook database

![](./img/Screenshot%209.png)

----
## Conclusion

By using Amazon RDS, we don’t need to handle database maintenance manually.
It saves time, gives backups automatically, and is easier to scale when needed.
