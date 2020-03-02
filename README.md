# Products_API
This API is meant for use with the Greenfield Product Portal: https://github.com/blackwayv/Greenfield-Product-Portal

NOTICE: This repository does not contain the data required to use the API properly. 

The microservice is designed to handle the 4 endpoints used in the Product Overview section of that project. These endpoints are optimized using table joins and sifting through the combined tables, and the data is indexed. Every endpoint responds in under 50ms, even under moderate stress (100 requests/second).

### Built With
* PostgreSQL
* Express
* Deployed to Amazon Web Services (AWS)

Stress tested with:
* New Relic
* K6
* Loader.io
