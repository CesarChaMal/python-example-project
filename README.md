## Introduction

This project is an example for a python command-line application structure with a unit testing framework.

## Prerequisites

* [docker](https://www.docker.com/)

## Running the Application

    docker-compose build
    docker-compose run project <command line arguments>
    
    docker build --tag python-example-project .
    docker push cesarchamal/python-example-project_project
    docker run --name python-example-project -p 5000:5000 python-example-project

## Testing

    docker-compose run test
