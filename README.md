
# Developer Search

I built this project based on Udemy with the purpose of studying.

Live Demo: [Click Here](https://devsrch.herokuapp.com/)

## Tech Stack
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) 
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

## Features
- Register/Login
- Create Projects on your Profile
- Add Skills to your Profile
- Send Messages to other Developers
- Leave Reviews on Projects
- Search Developers and Projects

## Installation

1. Clone this repo
2. Create a virtual environment and activate it
3. Install the requirements in the virtual environment 

    ```pip install -r requirements.txt```
4. Run the server
    
    ```python manage.py runserver```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DEBUG` - True or False

`SECRET_KEY` - Strong Random Key of Characters

`DATABASE_NAME` - Database name

`DATABASE_USER` - Database user

`DATABASE_PASSWORD` - Database password

`DATABASE_HOST` - Database host

`DATABASE_PORT` - Database port

`EMAIL_HOST_USER` - Email address

`EMAIL_HOST_PASSWORD` - Email or app password

`CLOUDINARY_URL` - Cloudinary image storage url
