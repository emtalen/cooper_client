### The Cooper Challenge

This is the Client of the first full stack application that we have created!
We have used Ruby on Rails 6.0.2.1 to create a backend API and used React 16.12.0 for the frontend and user interface. 

The application is a calculation of the Cooper test where the user can sign up, log in and then fill in the distance they ran in 12 minutes, gender and age. In the return the user gets a Cooper index. 
The user can show their previous results and will then get a line diagram with all their previous data. 

### Link: 
https://cooper-client.netlify.com/

To check out our repo of the Rails API:
https://cooper-api1.herokuapp.com/api/v1/
https://github.com/emtalen/cooper_api
https://github.com/pierre-1/cooper_api

### Tested With:
- We have used Cypress for acceptance test
- We have user Jest wih Enzyme for component testing

### User Stories: 
- As a User
In order to create my personal account
I would like to sign up a new account

- As a User
In order to use my account
I would like to be able to log in

- As a User
In order to get my personal Cooper index
I would like to fill in my personal values

- As a User
In order to know what my Cooper Index is
I would like to get back a message telling me the index

- As a User
In order to keep my previous results
I would like to be able to save them

- As a User
In order to keep that of my development
I would like to be presented with all my previous results

### Improvements/Updates:
There are a lot of improvement points on this project. 
There are som navigation issues, like a 'go back' button that needs to be added but also the possibility to log out. 
When the user creates an account there is no message saying that the account was successfully created, or that the user automatically is logged in. 
And of course the user should be able to log out from the application.

Apart from that we would also need to add styling so that the application becomes more user friendly and easier to interact with. 

### License: 
#### MIT-license