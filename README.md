# recepie-app-api
Recepie app api source code 
Reference: [Recepie Project](https://github.com/LondonAppDeveloper/recipe-app-api)

## Steps for the project deployment
* Building the docker app
```
docker build .
```
* Building the docker-compose image
```
docker-compose build
```
* Running the app inside the docker image
```
docker-compose run app sh -c "django-admin.py startproject app ."
```