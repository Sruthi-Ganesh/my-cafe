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
### Employees tab
<img width="1426" alt="Screenshot 2024-10-02 at 09 40 01" src="https://github.com/user-attachments/assets/9bc7e822-a197-453d-80ab-c329fe6d8b18">

### Create Employee Modal Form
<img width="1426" alt="Screenshot 2024-10-02 at 09 40 11" src="https://github.com/user-attachments/assets/88cefcc7-6e80-4b21-943d-779e54a3e026">

### Update Employee Modal Form (Prefilled with data)
<img width="1426" alt="Screenshot 2024-10-02 at 09 40 19" src="https://github.com/user-attachments/assets/789c3c7a-e2f6-461d-af4e-becd48494bce">

### Delete Employee
<img width="1426" alt="Screenshot 2024-10-02 at 09 40 26" src="https://github.com/user-attachments/assets/53d25cf0-6a49-47ec-bf16-6aa6bcf79c95">

### Cafe tab
<img width="1426" alt="Screenshot 2024-10-02 at 09 40 36" src="https://github.com/user-attachments/assets/f3d61d2b-8b10-4bee-a68c-5061547895e7">

### Create Cafe Modal Form
<img width="1426" alt="Screenshot 2024-10-02 at 09 40 44" src="https://github.com/user-attachments/assets/f879cb6b-f750-41ed-ad2d-28cc776f16a0">

### Update Cafe Modal Form
<img width="1426" alt="Screenshot 2024-10-02 at 10 06 10" src="https://github.com/user-attachments/assets/8fe3b32a-93f5-4c34-86fa-38acecf1c7b6">

### Update Cafe Modal Form (after file upload)
<img width="1426" alt="Screenshot 2024-10-02 at 10 06 53" src="https://github.com/user-attachments/assets/2bab7886-555e-440b-bc6e-03b6393a4ff9">




