# Testing go microservices
## How to make it worK

You need to install dep to make use of the dependencies

```sh
# Execute dep ensure to get the dependencies
$ dep ensure
```

To build and execute the services
```sh
docker-compose up
```

To start the development server 
```sh
$ cd frontend
$ yarn serve
```

You'll be able to access the server from url localhost:3000

