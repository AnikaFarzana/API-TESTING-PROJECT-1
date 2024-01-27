# API-TESTING-PROJECT-1

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console
newman run Project1.postman_collection.json -e Project1.postman_environment.json
```
- Run Command for Report: 
```console
newman run Project1.postman_collection.json -e Project1.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## API Documentation:
-https://documenter.getpostman.com/view/31698025/2s9YypFP6Q

## Test case list:
1. ### Create Student
        > Create Data Sets Using the Dynamic Random Variables.
        > In the test case you need to validate the following field values:
             1. Status Code
     
2. ### Get Student:
        > In the test case you need to validate the following field values:
             1. Status Code
             2. Length Of Response
     
3. ### Get Specific Student:
        > In the test case you need to validate the following field values:
             1. Status Code
             2. id
             3. First Name
   	         4. Middle Name
	         5. Last Name
  	         6. Date of Birth
    
4. ### Create Technical skills:
         > Create Data Sets Using the Dynamic Random Variables.
         > In the test case you need to validate the following field values:
             1. Status Code
     
5. ### Create a Student Address:
         > Create Data Sets Using the Dynamic Random Variables.
         > In the test case you need to validate the following field values:
             1. Status Code
             2. Status
             3. Message
    
6. ### Final Student Details:
         > In the test case you need to validate the following field values:
             1. Language
	         2. Year Of Experience
	         3. House Number
	         4. City
             5. Country
	         6. Mobile
             7. Current Address
      > 
 ## Newman Report Summary:
![Newman Report Summary](https://github.com/AnikaFarzana/API-TESTING-PROJECT-1/assets/146652775/43758f1b-437f-42c8-bfc0-6e5a7f1b76ed)
![image](https://github.com/AnikaFarzana/API-TESTING-PROJECT-1/assets/146652775/d1accb99-3933-4ce6-8c70-4b6b83c0f83a)


       
       
