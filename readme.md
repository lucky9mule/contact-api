1. We need to create following tables in mysql server

create table contact (contactid INT NOT NULL AUTO_INCREMENT, FirstName varchar(50), LastName varchar(50), DOB varchar(50), 
Gender varchar(50), Title varchar(50),  PRIMARY KEY ( contactid ));

create table contact_address (contactid INT NOT NULL, type varchar(50), number int, street varchar(50), Unit varchar(50), 
City varchar(50), State varchar(50), zipcode varchar(30));

create table contact_communication (contactid INT NOT NULL, type varchar(50),  value varchar(50), preferred varchar(50));

2. deploy the attached mule project into anypoint studio.

3. execute the following attached postman collection by sequence.



