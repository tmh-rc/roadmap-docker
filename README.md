# Docker Roadmap

## Requirements

- Need to know linux
- Unix basic command line
- Nano Editor

## Docker

  - Images
  - Container
  - [Docker Hub](https://hub.docker.com/)
  - Dockerfile
  - Port
  - Volume
  - Network
  - Docker Compose

## Assignments

- [Assignment 1](#assignment-1)
- [Assignment 2](#assignment-2)
- [Assignment 3](#assignment-3)
- [Assignment 4](#assignment-4)
- [Assignment 5](#assignment-5)

### Assignment 1

- Download ubuntu docker image
- Run downloaded image as container
- Enter bash shell into running container
- Create a `test.txt`
- Open a `test.txt` file with nano editor
- Write `Hello World!` and Save it.

### Assignment 2

- Create `index.php` file and write below code
```php
<?php

phpinfo();

```
- Create `Dockerfile` file
- In `Dockerfile`
  - Download `ubuntu` image
  - Install `apache` and setup
  - Install `PHP`
- Run image as container with port `8000`
- Open browser `http://localhost:8000`
- PHP information must be shown

### Assignment 3

- Create `Dockerfile` file
- In `Dockerfile`
  - Download `ubuntu` image
    - Install `apache` and setup
    - Install `PHP` and setup 
      - Install requirement `php-ext` to connect mysql
  - Download `mysql` image 
- Create `index.php` file
  - Create table & column
  - Insert data
  - Show data like [Todo App](#todo-app)
- Run apache-image as container with port `8000`
- Run mysql-image as container with port `3307`
- Open browser `http://localhost:8000`
- Must be shown [Todo App](#todo-app)

### Assignment 4

- [Assignment 3](#assignment-3) to show data until stop container

### Assignment 5

- Create `Dockerfile` file
- In Dockerfile
 - Download `nginx` image and setup
 - Download `php` image
    - Install `composer`
    - Install requirement `php-ext` to connect mysql
 - Download `mysql` image
- Create `Docker Compose` file
  - Setup above `Dockerfile` files
- Create a `laravel-docker` project
  - Setup `Env` file
  - Create table & column
  - Run ``php artisan migrate``
  - Insert data
  - Show data like [Todo App](#todo-app)
- Run apache-image as container with port `8000`
- Run mysql-image as container with port `3307`
- Open browser `http://localhost:8000`
- Must be shown [Todo App](#todo-app) until stop container

### Todo App
 ![screencapture-scm-ojt-github-io-todo-2023-02-28-11_26_12 (2)](https://user-images.githubusercontent.com/120365007/221758220-b835d565-462f-4947-b2eb-c9bafef67608.png)
