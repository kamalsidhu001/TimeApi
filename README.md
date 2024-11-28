# Toronto Time API

This is a Go-based application that interacts with a MySQL database to manage and retrieve the current time in the Toronto timezone. Designed for efficient time-zone-specific applications, this project demonstrates the integration of Go, SQL databases, and timezone management.

## Features

- **Database Integration**: Connects to a MySQL database to store and manage data.
- **Toronto Time Retrieval**: Retrieves and displays the current time in the Toronto timezone.
- **Efficient Time Zone Handling**: Leverages Go's time package for accurate timezone computations.

## Prerequisites

- [Go](https://golang.org/dl/) (version 1.16 or higher recommended)
- [MySQL](https://www.mysql.com/) database
- Go modules:
  - `github.com/go-sql-driver/mysql`
    
## Run Application
use go run main.go command to start the server.
Open your browser or postman to visit localhost:8080/current-time.

## Steps
1)Install the mysql on machine.

![image](https://github.com/user-attachments/assets/66d8b462-e0cf-4db5-bdad-4ae7d1198e56)

2)Create a new database and a table named time_log with at least two fields: id (primary key) and timestamp.

![image](https://github.com/user-attachments/assets/dffb5c42-f7d8-4344-adbb-0c6452a57058)

3)Run Go application with a web server.

![image](https://github.com/user-attachments/assets/332b198b-3fbd-422a-b842-81f92a486d31)

4)visit localhost:8080/current-time on your browser.

![image](https://github.com/user-attachments/assets/8425efec-08ee-412f-9ecb-af22e4cbb456)

5)When Connecting to  MySQL database from Go application.On each API call, it insert the current time into the time_log table.

![image](https://github.com/user-attachments/assets/23b55f17-d4cf-4923-8ea8-790292c1ec4d)






