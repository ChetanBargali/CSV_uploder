### Hosted link: [CSV-Uploader](https://csv-uploader-lb23.onrender.com)

# CSV-Uploader

CSV_Upload is a user-friendly web application designed for uploading and parsing CSV files. Developed using Node.js and Express, it offers a straightforward interface to facilitate seamless management of CSV data.


## Usage
Once you have the application up and running, you can start using it by following these steps:
* Upload CSV file.
* Show CSV file list.
* Delete CSV file.
* Read CSV file.

## Folder Structure
```
    CSV_uploader                               |--> file_viewer.css            
    |                                          |--> header.css
    |               |--->css------------------>|--> home.css
    |--->Assets---->|---> js-->file_viewer.js                   
    |                      
    |--->config---->|--->mongoose.js
    |          
    |                  |-->file_controller.js
    |--->controllers-->|-->home_controller.js
    |                  
    |               
    |--->models---->|-->csv.js
    |                      
    |              
    |--->routes---->|-->index.js
    |               
    |
    |--->uploads--->files            
    |             
    |              |--->file_viewer.ejs
    |--->views---->|--->home.ejs
    |              |--->layout.ejs
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
$ git clone https://github.com/ChetanBargali/CSV_uploder
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

