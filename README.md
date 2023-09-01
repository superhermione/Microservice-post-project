# A mini blog (Reactjs and Nodejs)

The project is a React-based web application that serves as a blog platform. It features a distributed architecture with multiple microservices to handle posts, comments, querying, and moderation functionalities. The project leverages asynchronous communication to minimize dependencies between services, enhancing efficiency.

## Architecture Components

* React Frontend: Handles UI and network requests to the microservices.
* Post Microservice: Manages blog posts.
* Comments Microservice: Manages comments on posts.
* Query Microservice: Aggregates and serves data from posts and comments.
* Moderation Microservice: Flags and filters comments based on language and approval status.
* Event-Bus: Facilitates communication between microservices by sending and receiving events.

## Technologies Implemented

* React: For building the user interface.
* Node.js: Backend for each of the microservices.
* Express.js: Web framework used in each Node.js microservice.
* Event-Bus: Custom or third-party service to handle event-based communication.
* Postman: For testing and interacting with the microservices via API requests.


## Key Features

* Asynchronous Communication: Used to decouple microservices and make the system more efficient and low dependency.
* Data Aggregation: The Query microservice compiles data from both Post and Comments services.
* Moderation: Comments undergo a moderation process to be flagged as pending, approved, or rejected.
* Event-Driven Architecture: All microservices interact with each other through the Event-Bus, allowing easy and dynamic data sharing and service updates.

## Video Walkthrough

* Here's a walkthrough of implemented features:
<img src="./assets/microservices blogpost.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' />

* The following image shows the communication among services
<img src="./assets/terminals-communication.jps" title='terminals-communication' width='' alt='terminals-communication' />
