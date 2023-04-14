The application reads the delivery locations from a JSON file and calculates the distance between the postman's current location and each delivery location using the Haversine formula. The application then returns the nearest delivery location to the postman.

The application has been implemented using the Model-View-Controller (MVC) architecture. The Model layer reads the delivery locations from the JSON file and performs the distance calculation. The View layer consists of the user interface, which allows the postman to enter his current location and displays the nearest delivery location. The Controller layer handles the communication between the Model and View layers.

This application runs on 8084 port.

Here are the endpoints you can use to perform CRUD operations:

Create a new location: POST http://localhost:8084/locations
Get a specific location by ID: GET http://localhost:8084/locations/{id}
Get all locations: GET http://localhost:8084/locations
Update a location: PUT http://localhost:8084/locations/{id}
Delete a location: DELETE http://localhost:8084/locations/{id}
Get nearest location: GET http://localhost:8084/locations?limit=2

You can use the appropriate HTTP methods (POST, GET, PUT, DELETE) along with the endpoints and required parameters to perform the desired CRUD operations.
