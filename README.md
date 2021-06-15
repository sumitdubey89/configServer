# configServer

to access files in server via url

localhost:portNo/<fileName>/<profile>

eg localhost:8888/application/default

for general config we can have application.properties or yml . 
But for properties specific to a microservice 
we should name the file as <microservice name>.yml or properties and all config in this file would be applied to 
the microservice with that name
Note thar spring.application.name must be defined as the name in client services

also can see the content of file:-
http://localhost:8888/<file-name>.<yml or properties>
http://localhost:8888/book-Webservice.properties


