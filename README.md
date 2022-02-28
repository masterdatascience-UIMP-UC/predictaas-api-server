# OpenAPI generated server

## Overview
This server was generated by the [OpenAPI Generator](https://openapi-generator.tech) project. By using the
[OpenAPI-Spec](https://openapis.org) from a remote server, you can easily generate a server stub.  This
is an example of building a OpenAPI-enabled aiohttp server.

This example uses the [Connexion](https://github.com/zalando/connexion) library on top of aiohttp.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software
- Python 3.5.2+

### Installing
To run the server, please execute the following from the root directory:

```
pip3 install -r requirements.txt
python3 -m openapi_server
```

and open your browser to here:

```
http://localhost:8080/api/v1/ui/
```

Your OpenAPI definition lives here:

```
http://localhost:8080/api/v1/openapi.json
```

## Running the tests
To launch the integration tests, use pytest:
```
sudo pip install -r test-requirements.txt
pytest
```

## Prevent file overriding

After first generation, add edited files to _.openapi-generator-ignore_ to prevent generator to overwrite them. Typically:
```
server/controllers/*
test/*
*.txt
```
