Collection of two submodule repositories: React and Django for cafe application

## Uses
- Python 3.12
- Django 5.1.1
- MySQL 9.0
- Node 20.17.0
- React 18.3.1
- Ag-Grid 32.2.1
- Tanstack Query 5.56.2
- Tanstack Router 1.58.x

## Setup

Run docker compose to setup
```
docker compose up -d --build
```

Go to http://localhost to view the web application

Go to http://localhost:8000/api/v1/swagger/ to see the swagger for backend

## Instructions
- Django migrations is preloaded with initial data of 20 employees and 5 cafes.
- There are two tabs Employee and Cafe
- Each tab has a filter at the top to filter by cafe name (employees) and location (cafes)
- Each tab has a button on bottom right to create a new row
- Each tab has a table with edit and delete option. Please scroll through the right if you are unable to see it

## DB Schema
![cafe-diagram](https://github.com/user-attachments/assets/7df0805a-5302-44d0-b614-7fb30d152375)

## Screenshots
* [View Screenshots](screenshot.md)



