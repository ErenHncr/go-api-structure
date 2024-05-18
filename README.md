## Go API Structure
This is a simple API structure for a Go application. The structure is designed to be modular and scalable. The structure is as follows:
  - **api** contains the code for the backend of the application. 
  - **storage** contains the code for database management.
  - **types** contains the code for structuring the data.
  - **utils** contains the code for utility functions.

Entry point of the application is in the ```main.go``` file. The ```main.go``` file initializes the database and starts the server. The server is started on port ```3000``` by default. ```listenaddr``` parameter in the ```main.go``` file can be changed to start the server on a different port.