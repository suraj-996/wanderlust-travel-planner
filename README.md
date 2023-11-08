


# WanderLust Travel Planner 

> WanderLust Travel Planner is an RESTful web service designed to provide customers with a personalized easy-to-utilize user experience for booking and purchasing tickets online. It stores customers' personal data records, scheduled routes, frequent trips, drop points, and other information.

> It has 6 modules Admin, User, Reservation, Bus, Route and Feedback.


# Features

- User and Admin authentication and validation using session uuid
- Admin can provide details like Bus Name, Bus Route, Bus Type –AC/non-AC, seats, departure time and arrival time
- Admin can provide details of route
- Admin can provide the confirmation of the seat to the User
- User can register by giving all the details
- User can book ticket by selecting Source and destination
- User can give feedback for bus experience
- User can cancel reservation

# Technology used 

- Java
- MySQL
- Spring Boot
- Spring data JPA
- RESTful api
- Hibernate
- Swagger
- Lombok
- Maven
- Postman
- Spring tool suite eclipse
- Git & GitHub

# Modules

- Login Logout Module
- Admin Module
- User Module
- Route Module
- Bus Module
- Reservation Module
- Feedback Module

# How To Run Our Project In Your Machine

1. Clone our Project into your system
    - Go to the folder location you want to clone
    - Open terminal 
    - Run command ``` https://github.com/suraj-996/wanderlust-travel-planner.git ```
2. Open your preferred Integrated Development Environment (IDE) such as Spring Tool Suite (STS) or IntelliJ IDEA.
3. Import the cloned project into your IDE:
   - In STS, click on "File" in the top menu, then select "Import"
   - In IntelliJ IDEA, click on "File" in the top menu, then select "Open"
4. Select the project directory where you cloned the repository ```BusTicketReservationSystem``` and click "OK" or "Open" to import the project.
5. You can run this project with MySQL db or H2 db
    - For MySQL, replace all the values under ```db specific properties``` and comment all specifications under ```H2 db``` in ```application.properties```
    - For H2, you can use the same or replace the values
6. Build the project and run ```BusTicketReservationSystemApplication```
7. To access database
    - For MySQL, you can use ```terminal``` as shown in explanation video or ```MySQL Workbench```
    - For H2, go to ```http://localhost:8008/h2-console/``` and fill proper details mentioned in ```application.properties``` under ```H2 db```
8. Open Swagger UI ```http://localhost:8008/swagger-ui/#/``` and execute the end points as in explanation video



