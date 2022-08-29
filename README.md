# Notes web
> developed by @davidprocode
### Project Description
This project was built using the Flask framework. I wanted to create a simple notes application that would allow me to have a secure notes database that could be accessed via web. I chose to use the flask-security package to handle the authentication. I created a user model that included username, password, email address. I then added some basic security checks to ensure that the user had entered their credentials correctly. If they did not enter them correctly, I would display an error message. Once the user was authenticated, I would redirect them to the home page where they could view their notes.
