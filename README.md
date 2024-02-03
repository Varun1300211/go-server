# Basic Go Server

This is a simple HTTP server written in Go. It serves static files and includes a couple of basic routes for demonstration purposes.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

Go version 1.16 or higher

### Installing

Clone the repository to your local machine:

```bash
git clone https://github.com/Varun1300211/go-server.git
cd basic-go-server

Build the server:

go build .

Running the server
To start the server, run the resulting executable:

./basic-go-server

The server will start on port 8080. You can access it at http://localhost:8080.

There are two routes available:

/: Serves static files from the ./static directory.
/form: Accepts POST requests with name and address fields in the form data.
/hello: Responds with "hello!" to GET requests.

Built With
Go - The programming language used