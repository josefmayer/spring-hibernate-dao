## Spring Hibernate DAO

### Technologies
JPA, Hibernate, Spring, MySQL <br />


### Project Structure
##### Model: <br />
JPA Entity <br />

##### DAO
CRUD operations: <br />
Interface <br />
Implementation <br />


##### Service
Interface  <br />
Implementation  <br />
Transactions  <br />


##### Spring Annotations
DAO:  <br />
org.springframework.stereotype.Repository <br />

Service:  <br />
org.springframework.beans.factory.annotation.Autowired <br />
org.springframework.stereotype.Service <br />
org.springframework.transaction.annotation.Transactional <br />




### Steps
##### MySQL
Start MySQL server  <br />

create database: <br />
*mysql –uroot –p –e “source src/main/resources/create_database.sql”*

create table:  <br />
*mysql –uroot –p –e “source src/main/resources/create_table.sql”*  <br />


##### Compile, create jar
*mvn clean compile package*  <br />


##### Run Application
*java -jar target/jar-name.jar* <br />



