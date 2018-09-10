# fast-food-2
![license](https://img.shields.io/github/license/mashape/apistatus.svg)
[![Build Status](https://travis-ci.org/kelvinndmo/fast-food-2.svg?branch=develop)](https://travis-ci.org/kelvinndmo/fast-food-2)
[![Coverage Status](https://coveralls.io/repos/github/kelvinndmo/fast-food-2/badge.svg?branch=develop)](https://coveralls.io/github/kelvinndmo/fast-food-2?branch=develop)
[![Maintainability](https://api.codeclimate.com/v1/badges/a236552c6eda78af4c69/maintainability)](https://codeclimate.com/github/kelvinndmo/fast-food-2/maintainability)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/9808cd8c1dfd4695a43de932c7af6e45)](https://www.codacy.com/app/kelvinndmo/fast-food-2?
[![PEP8](https://img.shields.io/badge/code%20style-pep8-orange.svg)](https://www.python.org/dev/peps/pep-0008/)
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

# Fast Food Fast

Fast food fast is a fast food delivery web application.

## How it Works

- An admin creates food items
- A user can view available food items 
- A user chooses on a food item and makes an order
- An Admin can accept or reject the order request from a user
- A user gets notified on his/her order status
- Accepted orders are delivered to the user

## Prerequisite

- [Python3.6](https://www.python.org/downloads/release/python-365/)
- [Virtua Environment](https://virtualenv.pypa.io/en/stable/installation/)

# Installation and Setup

Clone the repository below

```
git clone https://github.com/kelvinndmo/fast-food-2.git
```

### Create and activate a virtual environment

    virtualenv env --python=python3.6

    source env/bin/activate

### Install required Dependencies

    pip install -r requirements.txt



## Endpoints Available

| Method | Endpoint                        | Description                           |
| ------ | ------------------------------- | ------------------------------------- |
| POST   | /api/v1/orders                  | post a fooditem                       |
| GET    | /api/v1/orders                  | get all available foods               |
| PUT    | /api/v1/orders/<{id}>           | update on the status of an order      |
| GET    | /api/v1/orders/<{id}>           | get a specific food order             |
| DELETE | /api/orders/<{id}>              | delete a specific order by id         | 


### Testing

    nosetests

    - Testing with coverage

    nosetests --with-coverage --cover-package=app

### Author

Kelvin Onkundi Ndemo