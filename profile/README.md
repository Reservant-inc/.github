
<p align="center">
  <img alt="reservant" height="128" src="./.github/resources/reservant_logo.png">
  <h1 align="center">Reservant</h1>
  <p align="center">Easy-to-use platform for restaurants</p>
</p> 

## About
Reservant is more than a simple restaurant management system or any other POS. It is a platform that directly connects users with restaurant owners. Anyone can log in and participate in events related to different restaurants and make reservations. Restaurant owners can manage their restaurant and employees in an advanced way.

## Backend infrastructure
The backend software is responsible for handling requests and communicating with the database. The entire system is based on the .NET 8.0 platform. The system architecture is based on a monolithic infrastructure but with the possibility of development to a microservices infrastructure in the future. The documentation of the exposed endpoints is hosted by the server and to read it you need to:
* use docker compose do build the enviroment by running `docker compose up` command.
* go to `localhost:12038/swagger/index.html`.
  
Most of the endpoints require authorization so it's a good idea to use the default user, which will allow you to test the system:
* login: `JD`
* password: `Pa$$w0rd`

## Frontend UI

## Mobile App
