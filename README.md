# BreedTrak
> This challenge focuses on using GraphQl API's to replace existing REST API's in this app designed for a book search, using Google's book search.


The Assignment Your Challenge this week is emblematic of the fact that most modern websites are driven by two things: data and user demands. This shouldn't come as a surprise, as the ability to personalize user data is the cornerstone of real-world web development today. And as user demands evolve, applications need to be more performant.

This week, you’ll take a fully functioning Google Dogs API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and API. It's already set up to allow users to save dog searches to the back end.

To fulfill the Challenge, you’ll need to do the following:

Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.- - Modify the existing authentication middleware so that it works in the context of a GraphQL API.
Create an Apollo Provider so that requests can communicate with an Apollo Server.
Deploy the application to Heroku.
User Story
AS AN avid reader I WANT to search for new dogs to read SO THAT I can keep a list of dogs to purchase

Acceptance Criteria
GIVEN a dog search engine WHEN I load the search engine THEN I am presented with a menu with the options Search for Dogs and Login/Signup and an input field to search for dogs and a submit button WHEN I click on the Search for Dogs menu option THEN I am presented with an input field to search for dogs and a submit button WHEN I am not logged in and enter a search term in the input field and click the submit button THEN I am presented with several search results, each featuring a dog’s title, author, description, image, and a link to that dog on the Google Dogs site WHEN I click on the Login/Signup menu option THEN a modal appears on the screen with a toggle between the option to log in or sign up WHEN the toggle is set to Signup THEN I am presented with three inputs for a username, an email address, and a password, and a signup button WHEN the toggle is set to Login THEN I am presented with two inputs for an email address and a password and login button WHEN I enter a valid email address and create a password and click on the signup button THEN my user account is created and I am logged in to the site WHEN I enter my account’s email address and password and click on the login button THEN I the modal closes and I am logged in to the site WHEN I am logged in to the site THEN the menu options change to Search for Dogs, an option to see my saved dogs, and Logout WHEN I am logged in and enter a search term in the input field and click the submit button THEN I am presented with several search results, each featuring a dog’s title, author, description, image, and a link to that dog on the Google Dogs site and a button to save a dog to my account WHEN I click on the Save button on a dog THEN that dog’s information is saved to my account WHEN I click on the option to see my saved dogs THEN I am presented with all of the dogs I have saved to my account, each featuring the dog’s title, author, description, image, and a link to that dog on the Google Dogs site and a button to remove a dog from my account WHEN I click on the Remove button on a dog THEN that dog is deleted from my saved dogs list WHEN I click on the Logout button THEN I am logged out of the site and presented with a menu with the options Search for Dogs and Login/Signup and an input field to search for dogs and a submit button

Tech Used
JavaScript
Node.js
GraphQL
MongoDB
Mongoose
Bcrypt
Concurrance
Nodemon
Website
Github Repository: https://github.com/RauchDavis13/Dog_Search.git

Heroku deployed website: https://breedtrak.herokuapp.com/

Screen Shots
Home Page User Needs To Login ![Homepage]image

Login Page ...user already saved ![Login_SignUp]image (3)

Search for a Dog ....featuring newly setup Page Count and Published Date properties ![DogSearch]image (2)

Saved Dogs ....featuring newly setup Page Count and Published Date properties ![SavedDogs]Screen Shot 2022-04-07 at 6 54 11 PM

Thank You So Much To:
Instructor - Matt Kim
TA's
Valerie Flores
Kris Renaldi
Dustin Erwin,
Fellow Students
Kamyar Assadipour
Robert Evanik
K-Von Madison
Calvin Villanueva
Mohammed
Aanyah Cook
