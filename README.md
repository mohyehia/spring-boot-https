# spring-boot-https
Spring boot application that using SSL over HTTPS 

### Technologies Used
* Spring Boot
* Maven

### Prerequisites
Java 1.8 or greater, Spring boot 2.0 or greater, Maven, IntelliJ or Eclipse
 
### Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes:
* Generate a `self-signed-certificate` and create a `keystore` using the following commands:
* Open terminal and type the following commands:
* keytool -genkey -alias spring-boot-https keyalg RSA keysize 2048 validity 3650 keystore spring-boot-https.jks
* You will be asked to enter your password, first name, last name and other fields.
* Enter the password for the JKS or leave it the same as the keystore password.
* Move the jks to the resources folder of the application.
* import the project in IntelliJ or Eclipse.
* Or build the project using maven to get a jar file.
* Use the end point of `/hello` with `https`.