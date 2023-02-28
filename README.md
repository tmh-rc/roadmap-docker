# Docker Roadmap

## Prerequisites

- Basic knowledge of Operating Systems
- Basic knowledge of Linux
- Basic knowledge of Command Line Interface(CLI)
- Nano Editor
- YAML

## Docker Roadmap

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
- [Assignment 6](#assignment-6)

### Assignment 1

- Download ubuntu docker image
- Run downloaded image as container
- Enter bash shell into running container
- Create a `test.txt` in the container
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
  - Add index.php into apache document root
- Run image as container with port `8000`
- Open browser `http://localhost:8000`
- PHP information must be shown 

### Assignment 3

- Create 2 folders named `app` and `db`
- In `app` folder, create a `Dockerfile` file
- In `Dockerfile`
    - Download `ubuntu` image
    - Install `nginx` and setup
    - Install `PHP` and setup 
    - Install requirement `php-ext` to connect mysql
- Create `index.php` file
  - Create table & column for [Todo App](#todo-app) if does not exists
  - Write [Todo App](#todo-app)
- In `db` folder, create a `Dockerfile` file
- In `Dockerfile`
  - Download `mysql` image
  - Set database name, username, password
- Run app image as container with port `8000`
- Run db image as container with port `3307`
- Open browser `http://localhost:8000`
- Must be shown [Todo App](#todo-app)

### Assignment 4

- Do as [Assignment 3](#assignment-3) include `docker volume`
- Must change displaying screen while update the code in `index.php` without stopping the container

### Assignment 5
 
- Do as [Assignment 4](#assignment-4) use a `docker-compose.yml` file

### Assignment 6

- Create a [Todo App](#todo-app) using Laravel using Docker as [Assignment 5](#assignment-5)

### Todo App
![screencapture-scm-ojt-github-io-todo-2023-02-28-11_26_12 (3)](https://user-images.githubusercontent.com/120365007/221790363-8e7c75cd-a4b6-44c2-a8aa-28afbdb62dd4.png)

