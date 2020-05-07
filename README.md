# HOTEL API ENDPOINTS


REST API backend for [Hotel searching](https://hotelonclick.herokuapp.com/)

## Technolgies

* [Python 3.7](https://python.org) : Base development programming language
* [PostgreSQL](https://www.postgresql.org/) : Application backing relational databases for both staging and production environments
* [Django Framework](https://www.djangoproject.com/) : Host development framework built on top of python
* [Django Rest Framework](https://www.django-rest-framework.org/) : Provides API development tools for easy API development
* [CircleCI]() : Continous Integration and Deployment
* [Docker Engine and Docker Compose](https://www.docker.com/) : Containerization of the appication and services orchestration

## Getting Started

Few things you need to setup to get started, set up a virtual environment majorly for isolating installs, create a `.env` file from the example file and finally install all requirements in the `requirements.txt` files within the virtual environment.


# Change directory into the cloned folder and run the setup script
$ cd hotel-on-click
$ source venv/Scripts/activate

# Update .env file content as necessary.

# Start the application containers and open it in browser
$ docker-compose up


```

## Running Tests
# while docker is running,
$ docker-compose exec python manage.py test

```

## Deployment

Deployment to the `staging` environments is done automatically by CircleCI after test builds passes when there is a push or merge into `develop` branch.


