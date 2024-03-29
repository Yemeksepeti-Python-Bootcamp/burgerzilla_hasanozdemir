`
# BurgerZilla (Yemeksepeti & Patika.dev)

This microservice aims to manage customer orders from hamburger restaurants.
I provide this solution with microservice architecture under the limitation of REST-API

## Prerequisites
1. Python 3.9 
2. [Poetry](https://python-poetry.org/)  for dependency management
3. PostgresSQL

## Installation

I used Poetry for virtual environment because it's easier to use and manage the dependencies.

Those instructions valid for every microservice
Firstly initialize models on PostgresSQL 
Customer Service Example
```bash
start customer_database.bat
``` 
Run microservices
```bash
poetry run python run.py
```     

## Features

- Customer Order Management [CRUD]
- Restaurant Order Management [CRUD]

## Database Refence

Please follow the [link](4_project_docs/burgerzilla_db_schema.md)

## API Reference
Please follow the [link](4_project_docs/burgerzilla_api_reference.md)

## Tech Stack
**Language:** Python 3.9 

**Database Server:** PostgresSQL

**Libraries** : Please follow the [link](4_project_docs/burgerzilla_libraries_reference.md)



## Lessons Learned

1. What did you learn while building this project? 
    * I get used to more to Poetry
    * I increased my know how about relational databases for big projects
    * 

2. What challenges did you face and how did you overcome them?
   * My biggest challenge was about microservices. I knew definition, but I had no experience on it.
   * As a solution full one week I've done reading on microservices.io then I connected with Chris Richardson via Linkedin and find out answers for my question.
   * Finally, after 1 week I was able to design my architecture and database diagram
    

## Burgerzilla Architecture
![](4_project_docs/images/burgerzilla_architectrue.jpg)

**NOTE** : I knew normally for this project also webhook and load balancer is mandatory, unfortunately I had no time for it.

## Project Management

| ID  | Title                     | Status     |
|:---:|:--------------------------|:-----------|
|  1  | Project Started           | 01/29/2022 |
|  2  | Project Delivery Date     | 02/13/2022 |
|  3  | Total time I worked on it | 30 hours   |


## Project Evaluation

| ID  | Task               | Status |
|:---:|:-------------------|:-------|
|  1  | Project Structure  | OK     |
|  2  | PEP Standards      | OK     |
|  3  | Typing             | OK     |
|  4  | Testing            | NONE   |
|  5  | Documentation      | OK     |
|  6  | Dockerization      | NONE   |
|  7  | RabbitMQ Queue     | NONE   |
|  8  | JWT Implementation | NONE   |
|  8  | JWT Implementation | NONE   |
|  9  | Flake8 Lint Format | OK     |

## Footnote
1. Project is not completed.
2. I've spent on it totally 30 hours, but it was not enough for me.
3. I just added couple of endpoints and that's all.
4. Good luck to other candidates :)

## License

[Massachusetts Institute of Technology](https://choosealicense.com/licenses/mit/)

`
