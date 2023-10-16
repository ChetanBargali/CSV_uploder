### Hosted link: [CSV-Uploader](https://csv-uploader-lb23.onrender.com)

# CSV-Uploader

This web application which help you to Upload, Delete and Show CSV file . 
It is user specific app, which mean a user can track their habit, and mark it as done , or not done. 
The project is built using a tech stack consisting of Node.js for the server-side scripting.
Express for handling HTTP requests and routing.
MongoDB for storing and managing the data and EJS for rendering the views and templates.


## Usage
Once you have the application up and running, you can start using it by following these steps:
* Upload CSV file.
* Show CSV file list.
* Delete CSV file.
* Read CSV file.

## Folder Structure
```
CSV-Uploader
    Habit Tracker                              |--> forget_password.css            
    |                                          |--> header.css
    |               |--->css------------------>|--> home.css
    |--->assets---->|--->img                   |--> userSignIn.css
    |               |---> js-->home.js         |--> userSignUp.css
    |
    |               |--->flash_middleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport_local_strategy.js
    |
    |                  |-->habit_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->users_controller.js
    |
    |               |-->habit.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->habit.js
    |--->routes---->|-->index.js
    |               |-->users.js
    |
    |              
    |              |--->_header.ejs
    |              |--->daily_view.ejs
    |              |--->forget_password.ejs
    |--->views---->|--->home.ejs
    |              |--->layout.ejs
    |              |--->user-sign-in.ejs
    |              |--->user-sign-up.ejs
    |              |--->weekly_view.ejs
    |
    |-->node_modules
    |-->.gitignore
    |-->index.js
    |-->package-lock.json
    |-->package.json
    |-->README.md
```


## Installation
To run this application on your local machine, please follow these steps:

Clone this repository using the following command:
```
$ git clone https://github.com/ChetanBargali/Habit_Tracker
```
Install the required dependencies using the following command:
```
$ npm install 
```
Start the application using the following command:
```
$ npm start 
```
Open the application in your web browser by visiting the following URL:
```
$ http://localhost:8080 
```
