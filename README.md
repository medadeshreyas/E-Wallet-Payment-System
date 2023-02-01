 
# E Wallet Payment System

![E_Wallet_Payment_System](https://user-images.githubusercontent.com/105907169/203858500-b46d1c83-03c3-4842-b3f4-bdeefaa22d43.jpg)



## **WEB SERVICE : REST A.P.I.**


The Digital Wallet Application's REST API, developed by E PAY, offers customers the convenience and flexibility of being able to transfer money to and from their digital wallet and linked bank accounts. The API also allows for transactions with other registered customers on the E PAY platform and the ability to make payments directly to saved beneficiaries through their bank accounts. 

In addition to these features, the API also enables customers to manage their bills and perform basic CRUD operations, similar to other digital wallet applications. Security is of utmost importance, and the API Webservice implements customer and admin authentication and validation. 

The primary objective of the API is to provide customers with a streamlined and user-friendly digital wallet payment experience. The API is built on REST Architecture and can be consumed by any client that supports HTTP Protocol. 

This solution is perfect for anyone looking for quick, easy, and secure online transactions and can help small businesses, freelancers, and individuals manage their transactions and bills easily and securely. It can also be integrated with any application that supports REST API, making it suitable for a wide range of use cases.


## Tech Stack

- JAVA
- SPRING
- SPRINGBOOT
- HIBERNATE
- MAVEN
- J.D.B.C
- MYSQL
- POSTMAN

## Dependencies

- SPRING DATA JPA
- SPRING BOOT DEVTOOLS
- SPRING WEB
- HIBERNATE
- MYSQL DRIVER
- VALIDATION
- LOMBOK
- SWAGGER UI

## Features

 - Transfer money to and from digital wallet and linked bank accounts
 - Perform transactions with other registered customers on the E PAY platform
 - Make payments directly to saved beneficiaries through bank accounts
 - Manage bills and perform basic CRUD operations
 - Customer and admin authentication and validation
 - Streamlined and user-friendly digital wallet payment experience
 - Built on REST Architecture
 - Consumable by clients that support HTTP Protocol
 - Suitable for quick, easy and secure online transactions
 - Helps small businesses, freelancers and individuals manage their transactions and bills easily and securely
 - Can be integrated with any application that supports REST API
 - Suitable for a wide range of use cases.




## User Functionalities
- **Authentication Management**
  - Endpoint for Sign Up
  - Endpoint for Sign In
  - Endpoint for Sign Out

- **Financial Management**

  - Endpoint for Updating Personal Information and Address
  - Endpoint for Adding Bank Account Information
  - Endpoint for Updating Bank Account Information
  - Endpoint for Viewing Bank Account Information
  - Endpoint for Topping Up Wallet from Bank Account Balance
  - Endpoint for Transferring Money from Wallet to Bank Account
  - Endpoint for Transferring Funds to other Customers
  - Endpoint for Transferring Funds to Beneficiaries
  - Endpoint for Making Bill Payments
  - Endpoint for Checking Wallet Balance



##  Administrator Functionalities
    
- **Authentication Management**
  - Endpoint for Sign Up
  - Endpoint for Sign In
  - Endpoint for Sign Out

- **Admin Account Management**
  - Endpoint for Deleting Admins from Database

- **Customer Management**

  - Endpoint for Viewing Registered Customers
  - Endpoint for Viewing Customer Information
  - Endpoint for Viewing Customer Bank Accounts
  - Endpoint for Viewing Customer Beneficiaries
  - Endpoint for Viewing Customer Transactions




## Setting & Installation 

Install the Spring Tools Suite 
```bash
https://spring.io/tools
```

Install MySQL Community Server

```bash
https://dev.mysql.com/downloads/mysql/
```

Clone the Project

```bash
git clone https://github.com/medadeshreyas/E-Wallet-Payment-System
```

Open MySQL Server
```bash
Create a New Database in SQL: "e_wallet" 
```
Create a Admin For Your Database

```bash
INSERT INTO ADMIN VALUES('1001','admin_email','admin_first_name','admin_last_name','admin_mobile_number','admin_password');
```

Note for Admin & User
```bash
Admin Id : Min=1000, Max=1010 ; User Id : Enter Your Registered Mobile Number For Login, User Validation and Authentication. 
```


## Run Locally


Go to the Project Directory

```bas
Open the Payment Wallet Application Folder with S.T.S
```

Go to **src/main/resources > application.properties** & change your username and password (MySQL server username & password)

```bash
spring.datasource.username="username"

spring.datasource.password="password"
```

To change the **Server Port**

```bash
server.port=8088
```

Go to **com.masai package > Online_Shopping_System.java**

```bash
Run as Spring Boot App !
```
Open the following URL for Swagger-UI 
```bash
http://localhost:8088/swagger-ui/
```
 
 ## ER Diagram
 
![E-Wallet(1)](https://user-images.githubusercontent.com/105907169/203405312-629dd99b-0150-4025-9301-213571f2824e.png)


## URL
```bash
http://localhost:8088
```
## API REFERENCES

## Customer API Reference
![Screenshot 2022-11-25 at 02-28-34 Swagger UI](https://user-images.githubusercontent.com/105907169/203862673-27cb3929-3ed0-40de-ad43-c3147d3b5569.png)



## Wallet API Reference 


![Screenshot 2022-11-25 at 02-30-27 Swagger UI](https://user-images.githubusercontent.com/105907169/203862704-869fb029-4b83-473a-9eba-91c76c78b64d.png)

## Address API Reference


![Screenshot 2022-11-25 at 02-27-29 Swagger UI](https://user-images.githubusercontent.com/105907169/203862722-b0ef2994-cdb7-4774-91d1-421f1e6338c6.png)

## Bank Account API Reference


![Screenshot 2022-11-25 at 02-27-55 Swagger UI](https://user-images.githubusercontent.com/105907169/203862765-4db87a6c-496e-4520-8f34-75ab6e02c62c.png)

## Beneficiary API Reference


![Screenshot 2022-11-25 at 02-28-10 Swagger UI](https://user-images.githubusercontent.com/105907169/203862839-0e952f2d-f623-43f3-8138-7a2da3fbd3a1.png)


## Bill Payment API Reference

![Screenshot 2022-11-25 at 02-28-22 Swagger UI](https://user-images.githubusercontent.com/105907169/203862904-2508b507-a06f-479c-b3d7-069c3a78f203.png)


## Customer Login Logout API Reference


![Screenshot 2022-11-25 at 02-29-05 Swagger UI](https://user-images.githubusercontent.com/105907169/203862971-11f8bd90-090e-4012-b310-530076442020.png)


## Admin Login Logout API Reference


![Screenshot 2022-11-25 at 02-28-53 Swagger UI](https://user-images.githubusercontent.com/105907169/203863015-61d11dd5-efb6-42bd-9c81-75fd0091ac6f.png)

## Transactions API Reference

![Screenshot 2022-11-25 at 02-29-19 Swagger UI](https://user-images.githubusercontent.com/105907169/203863039-06043861-886f-48a0-871c-b5cc84aa348d.png)


## Contributions

Contributions are always **Welcome** !

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **Greatly Appreciated**.

If you have any ideas on how to improve this resume, please feel free to fork the repository and submit a pull request. Your contributions, no matter how big or small, are greatly appreciated and will help to make this repository even better.

In addition to contributing to the repository, you can also connect with me for further development and collaboration on this API. Together, we can continue to improve and evolve the API to meet the needs of the community.

We encourage you to give the repository a star and we thank you for your interest in this project. 

Your support is greatly appreciated.


## 🔗 Contact Me

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://medadeshreyas.github.io/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/shreyasmedade)

[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ShreyasMedade)

## Authors

- [Shreyas Vilas Medade](https://github.com/medadeshreyas)

- [Tejas Vilas Medade](https://github.com/tejasmedade)

## Acknowledgements

- [Masai School](https://www.masaischool.com/)
 

