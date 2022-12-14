# django-react-blog

Blog web application written using Javascript with React for Frontend, Python with Django for Backend and SQL as a default database.

## Features

- Publish posts as a verified staff member
- Read public posts
- Write/read comments
- Fully functional user with password veryfing/reseting using e-mail
- Authentication thanks to JWT Tokens


## Installation

1. First clone the repository to use it localy:

        git clone https://github.com/vaibhav-boraganve/blog-app.git

    Then install all required libraries  through:
2. create a virtual environmwnt using virtualenv env command and run below command to install all dependencies for django project.

        pip install -r requirements.txt

3. Now you need to create a Postgre database with name `blog_db` then do all the migrations using command:

        py manage.py makemigrations

        and:

        py manage.py migrate

        and:

        Also Create superuser and add data into database or via admin panel or using frontend alos u can add

4. For the frontend you need to run these commands from the `/frontend` folder:

        npm install

    to download all the needed NPM packages and then to start the frontend Dev server:

        npm run dev

5. Finally you can start the frontend server from base project folder by running:

        py manage.py runserver
