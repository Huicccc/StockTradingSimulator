## Introduction
- Created a database project for the stock trading simulator, using Graphical User Interface (GUI) and command line argument with Java and MySQL.
- Designed the conceptual ER diagram and built a relational data schema. Designed user flow chart for application.
- Accomplished CRUD operations and used database programming object to interact.

## CONCEPTUAL DESIGN
![OrangeSofa_ER_diagram](https://user-images.githubusercontent.com/105135459/206813256-df938771-76c5-4294-9c3e-3ebcb0249aa7.png)

## LOGICAL DESIGN
![image](https://user-images.githubusercontent.com/105135459/206814174-da24e242-4ecc-4694-a052-bcb5860a401a.png)

## USER FLOW
![image](https://user-images.githubusercontent.com/105135459/206814203-47e59a0d-869e-46e7-99b3-74b4e342f89d.png)

## README
Step 1 - Import database
- Open MySQL Workbench. Navigate to Server -> Data Import
- In import options, select “Import from Self-contained file”, choose the file path where you saved the provided dump file OrangeSofaTradeSimulatorDBDump.sql
- Click on ‘Start Import’ button at the bottom
- A new database named “orange_sofa_trade” should be created. Refresh the database to check.

Step 2 - Run Jar file
- Ensure JDK 11 version is installed: Check current version: ```java -version```. Check Java versions: ```/usr/libexec/java_home -V```. Switch to Java 11:   ```export JAVA_HOME=`/usr/libexec/java_home -v 11.0` ```.
- Run the command ```java -jar OrangeSofaTradeSimulator.jar```. Follow the instructions in the terminal to login with mysql root username and password to connect to MySQL Workbench.


<img width="906" alt="Screen Shot 2022-12-09 at 10 41 53 PM" src="https://user-images.githubusercontent.com/105135459/206827453-1b7b3f90-a52f-4a51-b4b9-4c64adc3cd78.png">

<img width="512" alt="Screen Shot 2022-12-09 at 10 38 44 PM" src="https://user-images.githubusercontent.com/105135459/206827475-737b7cc2-deda-4f8a-bc7d-7a31d288e229.png">

<img width="769" alt="Screen Shot 2022-12-09 at 10 39 02 PM" src="https://user-images.githubusercontent.com/105135459/206827490-3368d3f1-35ca-4a3f-bb80-f16c7be300bc.png">

<img width="412" alt="Screen Shot 2022-12-09 at 10 39 31 PM" src="https://user-images.githubusercontent.com/105135459/206827494-25326a95-238c-4c08-a674-979229cb0a29.png">

<img width="412" alt="Screen Shot 2022-12-09 at 10 40 48 PM" src="https://user-images.githubusercontent.com/105135459/206827499-e4d3d1ba-7d0d-4c4a-972e-669ede802036.png"> <img width="412" alt="Screen Shot 2022-12-09 at 10 40 51 PM" src="https://user-images.githubusercontent.com/105135459/206827509-767edcee-ca8d-47ae-8b10-fa90e98e33ee.png">
