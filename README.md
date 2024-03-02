# A-plus - Online Learning Platform

## Motivation

A-plus is a university project for CSEN704 - Advanced Computer Lab course @ GUC, the main purpose of the project was
 to build a complete Online Learning Platform,where instructors can post a course and students all over the world can subscribe to them.

## Build Status
Currently A-plus is a Minimum Value Product (MVP), which can be used by customers and let us observe how they interact with the system.

Currently there are no known bugs/errors in the system, but if you find any pull requests are more than welcomed.

## Technology used
This web application was build with MERN stack:

- MongoDB as our NoSQL database
- ExpressJS as our NodeJS wrapper
- ReactJS for our view library
- NodeJS for server-side JS runtime enviroment

Additional libraries used:
- Axios - promise-based http client
- mongoose - Object Document Mapper (ODM) of choice
- Our dependencies and their verison :
    - "@emotion/react": "^11.10.5",
    - "@emotion/styled": "^11.10.5",
    - "@material-ui/core": "^4.12.4",
    - "@material-ui/icons": "^4.11.3",
    - "@material-ui/styles": "^4.11.5",
    - "@material-ui/system": "^4.12.2",
    - "@material-ui/utils": "^4.11.3",
    - "@mui/icons-material": "^5.11.0",
    - "@mui/lab": "^5.0.0-alpha.113",
    - "@mui/material": "^5.11.2",
    - "@paypal/react-paypal-js": "^7.8.2",
    - "@sweetalert/with-react": "^0.1.1",
    - "axios": "^1.2.0",
    - "blob": "^0.1.0",
    - "body-parser": "^1.20.1",
    - "body-parser-zlib": "^1.0.2",
    - "bootstrap": "^5.2.3",
    - "bootstrap-4-react": "^0.0.59",
    - "cors": "^2.8.5",
    - "country-to-currency": "^1.0.6",
    - "dotenv": "^16.0.3",
    - "express": "^4.18.2",
    - "express-session": "^1.17.3",
    - "flux": "^4.0.3",
    - "googleapis": "^109.0.1",
    - "hoist-non-react-statics": "^3.3.2",
    - "i": "^0.3.7",
    - "js-file-download": "^0.4.12",
    - "material-icons": "^1.13.1",
    - "mdb-react-ui-kit": "^5.0.0",
    - "moment": "^2.29.4",
    - "mongoose": "^6.7.4",
    - "node-blob": "^0.0.2",
    - "node-sass": "^8.0.0",
    - "nodemailer": "^6.8.0",
    - "nodemon": "^2.0.20",
    - "popup": "^0.0.3",
    - "prop-types": "^15.8.1",
    - "react": "^18.2.0",
    - "react-bootstrap": "^2.7.0",
    - "react-bootstrap-country-select": "^1.0.0",
    - "react-datepicker": "^4.8.0",
    - "react-dom": "^18.2.0",
    - "react-is": "^18.2.0",
    - "react-native-country-picker-modal": "^2.0.0",
    - "react-player": "^2.11.0",
    - "react-select": "^5.5.8",
    - "react-select-country-list": "^2.2.3",
    - "react-toastify": "^9.1.1",
    - "reactjs-popup": "^2.0.5",
    - "sass": "^1.56.2",
    - "shards-react": "^1.0.3",
    - "sweetalert": "^2.1.2",
    - "video-react": "^0.16.0"
## Some screenshots from the website

-Login Page
![image](https://user-images.githubusercontent.com/116280403/210184548-27c15026-ffc2-4d54-9330-4a1b0893d82f.png)

-Home Page
![image](https://user-images.githubusercontent.com/105214594/210189084-bf7f38d1-52c6-4149-b0e4-860991a2e74f.jpg)

-My courses
![image](https://user-images.githubusercontent.com/116280403/210184803-df24eecd-14fd-46ee-a6b9-f1022b8e3202.png)

-Course Info
![image](https://user-images.githubusercontent.com/116280403/210185014-694f93f4-3507-423c-aae6-28a055470adc.png)

-Quiz Answers
![image](https://user-images.githubusercontent.com/116280403/210185221-f706fb24-ab60-4d12-b69d-42951320c7fa.png)

-Refund Request
![image](https://user-images.githubusercontent.com/116280403/210185303-c91bbc3c-8797-498e-ac1a-a8abcdeb0207.png)

-Register Page
![image](https://user-images.githubusercontent.com/116280403/210185378-094f8349-842f-40dd-a12b-d4e34990585a.png)

-User Profile
![image](https://user-images.githubusercontent.com/116280403/210185406-d0a9a458-64d4-466e-b415-1dd3941ae562.png)



## Features

- Visually appealing UI that helps the user enjoy his time browsing the website
- UX designed to guide the user smoothly throughout the website with recovery from error, reversibility and learnability
- Responsive design which gives the user feedback about what is currently happening
## Installation

- Make sure you have [NodeJS](https://nodejs.org/en/) installed on your machine

  You can check by running

         node -v

  in your terminal to make sure NodeJS is setup correctly
  - Make sure to include .env file in the backend directory

### required installations:
1.  In your terminal navigate to

         /A-plus

2.  Install required packages by running

         npm i

### How to run the frontend:

1.  In your terminal navigate to

         /A-plus/frontend


2.  Install required packages by running

         npm i

3.  Spin up the development server using

          npm start

    open your browser at http://localhost:3000

### How to run the backend:

1.  In your terminal navigate to

         /A-plus/backend

2.  Install nodemon by running

         npm i -g nodemon


3.  Spin up the development server using

          nodemon server

    It will run on http://localhost:5000


## API reference
As we use query for all our require(s) from the server we have included screenshots with the included query requirements for all functions referenced 

### /api/user

1.  /login (post) 

    Request query
![image](https://user-images.githubusercontent.com/105214594/210189011-53874759-dd3a-45fe-ba11-f13981b231dc.jpg)

### /api/user
1.  /create (post)
    
    Request query
     ![image](https://user-images.githubusercontent.com/105214594/210189016-d3b9d2e3-f060-4860-a727-ad71811e3daa.jpg)

### /api/subtitles
1. /addsubtitle (post)
    Request query
      ![image](https://user-images.githubusercontent.com/105214594/210189020-f4a44f9e-e7f4-4cee-83c2-a8ebe599110d.jpg)

2. /updateSubtitles (put)
    Request query
      ![image](https://user-images.githubusercontent.com/105214594/210189025-a20ed639-ac1d-4742-8966-cbf6d4aaf2b1.jpg)

### /api/trainee
1. /calculateAverageRating (post)
    Request query
     ![image](https://user-images.githubusercontent.com/105214594/210188903-a95acab8-08cf-444c-be99-457902824dc9.jpg)

### /api/corporateTrainee
1. /getMarkBs (post)
    Request query
    ![image](https://user-images.githubusercontent.com/105214594/210188976-352e7c1f-9cbd-48eb-ada2-0a5c1662b3b3.jpg)

### /api/progress
1. /addProgress (post)
    Request query
    ![image](https://user-images.githubusercontent.com/105214594/210188973-86736441-9837-4b90-8ede-764b07d9e45d.jpg)

## Tests

- Postman can be used to test the functionality of different API endpoints make sure to attach bearer token if endpoint requires token

- Any browser can be used to test the functionality of the frontend webpages and web compenents

## How to use

### What can you do on the portal



### If you logged in as an admin:


- You can add another administrator with a set username and password

- Add instructors and create their usernames and passwords

- Add corporate trainees and create their usernames and passwords

- View course requests from corporate trainees

- Grant corporate trainees access to specific courses

- Set a promotion (% sale) for specific courses, several courses or all courses

- View reported problems and mark them as "pending" or "resolved"

- refund an amount to a trainee to their wallet




### Individual Trainee:

- Starts as a guest and then he can sign up for an account as an individual trainee using a username, email, password, first name, last name and gender

- Select his country

- View and accept the website/ company refund/ payment policy while signing up

- Log in using a username and password

- Log out

- View all the titles of the courses available including the total hours of the course, course rating, and price

- Filter the courses based on a subject and/or rating and/or price

- Search for a course based on course title or subject or instructor

- Choose a course from the results and view (but not open) its details including course subtitles, excercises , total hours of each subtitle, total hours of the course and price (including % discount if applicable) according to the country selected

- View a preview video of the course and the course outline before registering for it

- View the most viewed/ most popular courses

- Enter their credit card details to pay for a course they want to register for

- Pay for a course

- Open all the items inside a course he/she is registered for including videos and excercises

- Change his/her password

- Receive an email to change a forgotten password

- Rate an instructor or a course

- Solve a multiple choice exercise by choosing the correct answer and submit the answers

- View his/her grade from the exercise

- View the questions with the correct solution to view the incorrect answers

- Watch a video from a course he/she is registered for

- See his/her progress in the course as a percentage of how much of the course has been completed so far

- Receive a certificate as a PDF after completing the course via email and download it as a PDF

- Write notes while watching the video and download it as a PDF

- Request a refund only if less than 50% of the course has been attended

- See a list of all the courses he/she is enrolled in on their profile

- Report a problem with a course. The problem can be "technical", "financial" or "other"

- See all previously repoted problems and their statuses

- Follow up on an unresolved problem

- View the amount available in their wallet from refunded courses



### Corporate Trainee:

- Log in using a username and password

- Log out

- Select his country 

- View all the titles of the courses available including the total hours of the course and course rating

- Filter the courses based on a subject and/or rating

- Search for a course based on course title or subject or instructor

- View a preview video of the course and the course outline before registering for it

- View the most viewed / most popular courses

- Open all the items inside a course he/she is registered for including videos and excercises

- Change his/her password

- Receive an email to change a forgotten password

- Rate an instructor or course

- Solve a multiple choice exercise by choosing the correct answer

- Submit the answers to the exercise after completing it

- View his/her grade from the exercise

- View the questions with the correct solution to view the incorrect answers

- Watch a video from a course he/she is registered for

- See his/her progress in the course as a percentage of how much of the course has been completed so far

- Receive a certificate as a PDF after completing the course via email

- Download the certificate as a PDF from the website

- Write notes while watching the video

- Download the notes as a PDF

- See a list of all the courses he/she is enrolled in on their profile

- Report a problem with a course. The problem can be "technical", "financial" or "other"

- See all previously repoted problems and their statuses

- Follow up on an unresolved problem

- Request access to a specific course they do not have access to



### Instructor :

- Log in using a username and password

- Log out

- View and accept the website/ company refund/ payment policy while signing up

- View and accept the contract which includes all the rights to the posted videos and materials as well as the % taken by the company on each video per registered trainee

- Select his country 

- View all the titles of the courses available including the total hours of the course and course rating

- View the price of each course

- Filter the courses based on a subject and/or rating and/or price

- Search for a course based on course title or subject or instructor

- Choose a course from the results and view (but not open) its details including course subtitles, excercises , total hours of each subtitle, total hours of the course and price (including % discount if applicable) according to the country selected

- View a preview video of the course and the course outline before registering for it

- View the most viewed/ most popular courses

- View all the titles of the courses given by him/her

- Filter the courses given by him/her based on a subject or price

- Search for a course given by him/her based on course title or subject or instructor

- View the ratings and reviews on all his/her courses

- View the amount of money owed per month

- Create a new course and fill in all its details inclding title, subtitles, price and short summary about the entire course
 
- Upload a video link from YouTube under each subtitle and enter a short description of the video

- Upload a video link from YouTube as a preview to the course

- Create a multiple choice exam with 4 choices per question

- Set the answers (not visible for the trainee) for multiple choice exercises

- View his/her rating and reviews as an instructor

- Edit his/her mini biography or email

- Define a promotion for the course (% discount) and for how long

- Change his/her password

- Receive an email to change a forgotten password

- See a list of all the courses he/she is enrolled in on their profile

- Report a problem with a course. The problem can be "technical", "financial" or "other"

- See all previously repoted problems and their statuses

- Follow up on an unresolved problem


## Contribute

Pull requests are more than welcomed in this repository, feel free to open one to fix a bug, enhance a feature or introduce a new one.

## Credits

Mario Maurice
Abdelrahman Yasser
Gamila Hesham
Ahmed Hicham
Mina Shady
