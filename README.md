# API-Testing-work
In this I tested a collection API's.

Documentation Link: https://restful-booker.herokuapp.com/apidoc/index.html#api-Booking-UpdateBooking

Tools used:
- Postman
- JS
- Newman
- CSV data

Testing CSV Data:
-For testing the csv data the variable name of csv data and postman's body data both should be same. (Example - in csv file -Firstname, in body - Firstname) 

Newman Install command:
- npm install -g newman

Normal Report Install Command:
- npm install -g newman-reporter-html
Decorated Report Install Command: 
- npm install -g newman-reporter-htmlextra

Run Command for normal report generator:
- newman run “Collection Link” -e EnvironmentName.json -r cli,html
Run Command for decorated report generator:
- newman run “Collection Link” -e EnvironmentName.json -r cli,htmlextra




