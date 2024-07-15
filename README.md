# Crypto Wallet API Testing Project

## Author
**Vikas Kumar**

## Description
This project involves automating the testing of a mock Crypto Wallet API using Postman, Rest Assured, and Cypress. The API has various endpoints that allow users to register, login, retrieve wallet balances, list transactions, transfer cryptocurrency, calculate transaction fees, and get exchange rates.

## Setup and Run Instructions

### Postman
1. Download and install [Postman](https://www.postman.com/downloads/).
2. Import the Postman collection:
    - Open Postman and click on "Import".
    - Import the provided Postman collection JSON file.
3. Run the requests in the Postman collection to validate the API endpoints.

### Rest Assured
1. Install Java (JDK 8 or later).
2. Install an IDE like [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) or [Eclipse](https://www.eclipse.org/downloads/).
3. Create a new Maven project and add the following dependencies to your `pom.xml` file:
    ```xml
    <dependencies>
<!-- https://mvnrepository.com/artifact/io.rest-assured/rest-assured -->
<dependency>
    <groupId>io.rest-assured</groupId>
    <artifactId>rest-assured</artifactId>
    <version>4.5.1</version>
    <scope>test</scope>
</dependency>
<!-- https://mvnrepository.com/artifact/org.testng/testng -->
<dependency>
    <groupId>org.testng</groupId>
    <artifactId>testng</artifactId>
    <version>7.7.1</version>
    <scope>test</scope>
</dependency>
<!-- https://mvnrepository.com/artifact/com.googlecode.json-simple/json-simple -->
<dependency>
    <groupId>com.googlecode.json-simple</groupId>
    <artifactId>json-simple</artifactId>
    <version>1.1.1</version>
</dependency>
<dependency>
    <groupId>org.jsoup</groupId>
    <artifactId>jsoup</artifactId>
    <version>1.14.3</version>
</dependency>
<dependency>
   <groupId>io.rest-assured</groupId>
   <artifactId>json-path</artifactId>
   <version>4.5.1</version>
   </dependency>
<dependency>
   <groupId>io.rest-assured</groupId>
   <artifactId>xml-path</artifactId>
   <version>4.5.1</version>
   </dependency>
<dependency>
   <groupId>io.rest-assured</groupId>
   <artifactId>json-schema-validator</artifactId>
   <version>4.5.1</version>
   </dependency>
  </dependencies>
  
4. Copy the provided Rest Assured Java code into your project.
   
5. Run the test methods to validate the API endpoints.

### Cypress
1. Install [Node.js](https://nodejs.org/) (which includes npm).
2. Create a new directory for the project and navigate into it:
    ```sh
    mkdir crypto-wallet-api-tests
    cd crypto-wallet-api-tests
    ```
3. Initialize a new npm project:
   
    npm init -y
   
4. Install Cypress:
   
    npm install cypress --save-dev
  
5. Create a new file `cypress/integration/crypto_wallet_api_tests.spec.js` and copy the provided Cypress test code into it.

6.Open Cypress and run the tests:
   
    npx cypress open
   

## Dependencies and Prerequisites
- **Postman**: Download and install from [Postman](https://www.postman.com/downloads/).
- **Java (JDK 8 or later)**: Download and install from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).
- **Maven**: Usually comes with IDEs like IntelliJ IDEA or Eclipse.
- **Node.js and npm**: Download and install from [Node.js](https://nodejs.org/).
- **Cypress**: Install via npm using `npm install cypress --save-dev`.

With these steps, you should be able to set up and run the project to validate the Crypto Wallet API endpoints using Postman, Rest Assured, and Cypress.
