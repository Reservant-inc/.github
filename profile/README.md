
<p align="center">
  <img alt="reservant" height="128" src="../.github/resources/reservant_logo.png">
  <h1 align="center">Reservant</h1>
  <p align="center">Easy-to-use platform for restaurants</p>
</p> 

## About
Reservant is more than a simple restaurant management system or any other POS. It is a platform that directly connects users with restaurant owners. Anyone can log in and participate in events related to different restaurants and make reservations. Restaurant owners can manage their restaurant and employees in an advanced way.

## Backend infrastructure
[The backend software](https://github.com/Reservant-inc/reservant-backend) is responsible for handling requests and communicating with the database. The entire system is based on the .NET 8.0 platform. The system architecture is based on a monolithic infrastructure but with the possibility of development to a microservices infrastructure in the future. The documentation of the exposed endpoints is hosted by the server and to read it you need to:
* clone [backend's repo](https://github.com/Reservant-inc/reservant-backend)
* use docker compose to build the enviroment by running `docker compose up` command (inside the repo's folder).
* go to `localhost:12038/swagger/index.html`.
  
Most of the endpoints require authorization so it's a good idea to use the default user, which will allow you to test the system:
* login: `JD`
* password: `Pa$$w0rd`

## Frontend
[The frontend](https://github.com/Reservant-inc/reservant-frontend) of our system can be divided into a web application and a mobile application (more info below). The web application should be accessible from basically any modern browser. Thanks to TypeScript and React framework, the application has modern look and reactive architecture. To run the application, you need to 
* clone the repo
* create the environment variable `export RESERVANT_APP_SERVER_IP={BACKEND_IP}:{BACLEND_PORT}`.
* execute the `docker compose up` command.

## Mobile App
[The mobile application](https://github.com/Reservant-inc/reservant-mobile) is available (at the moment) only for the Android operating system. This does not mean, however, that the project will not be expanded to include support for IOS in future, Rome wasn't built in a day. The app's UI was written based on Jetpack compose technology, which means fast writing of a beautiful-looking user interface. The app supports android sdk version 26 (Android 8.0). The application was written based on MVVM architecture.

## Contributors

### Backend
<a href="https://github.com/Reservant-inc/reservant-backend/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Reservant-inc/reservant-backend" />
</a>

### Frontend
<a href="https://github.com/Reservant-inc/reservant-frontend/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Reservant-inc/reservant-frontend" />
</a>

### Mobile
<a href="https://github.com/Reservant-inc/reservant-mobile/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Reservant-inc/reservant-mobile" />
</a>

### Tests
<a href="https://github.com/Reservant-inc/reservant-tests/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Reservant-inc/reservant-tests" />
</a>
