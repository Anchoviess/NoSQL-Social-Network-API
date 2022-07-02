# NoSQL-SocialNetwork-API

This is an API for a social network web application where users can share their thoughts, react to friends' thought's, and create a friend list. It utilizes a NoSQL database to handle large amounts of unstructured data.

## Description

  MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. NoSQL Social Network API is a backend database that is designed to use with a social media application. Users can post thoughts, while other users can post reactions to those thoughts. This app is a social network which allows users to create thoughts and react to other peoples thoughts. When the User enters the command to invoke the application, the server is started and Mongoose models are synced to the MongoDB database. When the User opens API GET routes in Insomnia for 'users' and 'thoughts', the data for each of these routes is displayed in a formatted JSON. When the User tests API 'POST', 'PUT' and 'DELETE' routes in Insomnia, then they are able to successfully create, update and delete users and thoughts in the database. When the User tests API 'POST' and 'DELETE' routes in Insomnia, then they are able to successfully create and delete reactions to thoughts and add and remove friends to a user's friend list.
  
## Built With

   -NoSQL(MongoDB)
  - Mongoose
   - Express.js

## Instructions 
    Install MongoDB
    Run the following commands in the integrated terminal (Visual Studio Code)
        - npm init -y
        - npm install express
        - npm install mongoose
    Start the server
         - npm start
    Install Insomnia
    - Open Insomnia Core to test API routes
    - Create New requests: GET, POST and PUT to visualize and manipulate the data pulled from the database.

## Screenshots

<img width="1440" alt="Screen Shot 2022-07-01 at 5 13 35 PM" src="https://user-images.githubusercontent.com/97990379/176979385-550fe656-acd9-457e-90a7-367866788936.png">

<img width="1440" alt="Screen Shot 2022-07-01 at 5 14 20 PM" src="https://user-images.githubusercontent.com/97990379/176979390-703bed57-646f-4a30-8973-7fb98de4c35d.png">


<img width="1440" alt="Screen Shot 2022-07-01 at 5 13 46 PM" src="https://user-images.githubusercontent.com/97990379/176979396-6fba8db8-263b-4ff7-bf92-3272e1f619fc.png">


### Walkthrough Video


https://user-images.githubusercontent.com/97990379/176979479-8b5eb860-2e2a-4834-bd25-1d43849c603e.mov


##### Youtube link:

https://youtu.be/Vj64gPePak0



   

#### Contribution

Contact me via my github profile:

-Anthony Ledesma (github.com/Anchoviess)
