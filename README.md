CDIT Assignment (Spring Boot and Java)

# SpringBoot MVC + MySQL + BufferedReader

This application uses
1. MySQL
2. JPA
3. MVC 
4. Maven
5. Buffered Reader to read CSV file

To use this application, 
1. git clone the repository ```https://github.com/txinyi/Spring_CSV_BufferedReader.git```
2. create MySQL database based on the credentials mentioned in ```application.properties```
4. CSV file can be found in ```src/main/resources/users.csv```
3. Run the application

## Input
Upload CSV files
![Index](https://github.com/txinyi/Spring_CSV_BufferedReader/blob/master/readme/indexJSP.PNG?raw=true)


## Output
Epxose outputs on users with valid salary (0 <= salary <= 4000) in Json
![JsonEndPoint](https://github.com/txinyi/Spring_CSV_BufferedReader/blob/master/readme/usersEndpoint.PNG?raw=true)

