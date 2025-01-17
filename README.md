Onliine-Banking-Management-System
RUN PROCESS:
First You should connect your java ide with JDBC(Java Database Connectivity) Here the full reference of How to connect JDBC with MY SQL : https://www.javatpoint.com/example-to-connect-to-the-mysql-database

2.you should create a database with name of "Banksystem" 
create table signup (formno varchar (30),name varchar (30),fname varchar (30),dob varchar(60),gendar varchar (30),email varchar (60),marital varchar (30),address varchar (30),city varchar(30),pincode varchar (30),state varchar (600));
 create table signup2(form_No varchar (30),religion varchar(30),category varchar(30),income varchar(30),education varchar (30),occuption varchar (30),pan varchar(30),aadhar varchar (30),seniorcitizen varchar (30));
 create table signup3 (form_No varchar(30),Account_type varchar(40),card_No varchar(30),pin varchar(30),facility varchar(400));
create table login (form_No varchar (30),card_No varchar (50),pin varchar (30));
create table bank(pin varchar(10),date varchar(50),type varchar(20),amount varchar(20));
connection= DriverManager.getConnection("jdbc:mysql://localhost:3306/banksystem","root","aadubey");
By default username is already root.
you should run login.java file
if click new Customer first you get Application form :
after register you can  get Card number and pin number login as exist customer by using Card Number and Pin Number and can see all details of his
You can Select your transction like Cash Withdrawl ,Fast Cash,Pin Change, Balance Enquiry,Mini Statement if you select mini statement then show your latest mini statement
