# Storage_Service_DBManagement  

Storag_Service_DBManagement consist of an SPI that provides a Java interface for the main DB Management operations, such as:  

* connection;  
* disconnection;  
* execution of a SQL command.

This project contains also another Java interface that extends the previous one by adding specific operations for OrientDB data management, such as:  

* commit;
* rollback;  
* delete;  

Finally it contains a concrete Java Class that implements all the methods defined in the described interface.  

## Usage 

Storage_Service_DBManagement project is a Maven Project and it is configured among the dependencies of the Storage Service project. It is required to execute a Maven Build of it in order to make it correctly usable from the other projects.  