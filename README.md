
### R1 Description of your website, including:
 **Purpose**

  Smoothies have gained fame over the past years for a host of health benefits with the added bonus of being tasty!  And with the internet allowing the exchange of information at wildfire-pace, this app makes use of people’s passion for smoothies! It allows the users to view smoothie recipes from their favourite categories and post comments on what they think of them. It also allows users to post their recipes, so that others can try them and enjoy its goodness! We call this app “Smoothiverse” because we feel it offers the universe of smoothies in terms of variety.

<br>

**Functionality / features**
- The navbar helps users in easily navigating to the page of their choice
- Registration and authentication of user
- Signed in users can create smoothie recipes of their choice
- Owners of recipes have the ability to edit and delete their listings
- All users can view smoothie recipes
- Signed in users can comment on the posts they like
- Users can filter smoothies on the basis of categories

<br>

**Target audience**
Smoothiverse appeals to 
- people wanting a post-workout smoothie
- People who have diabetes and want smoothies specific to their diet
- pregnant/breastfeeding women looking for extra nutrients,
- office-goers who want a quick, healthy (and filling!) recipe 
- parents looking to sneak in something nutritious into their children’s meals. 
- those allergic to nuts and looking for nut free smoothie recipes
- those looking for weight-loss recipes
- those who love to tell their Smoothie recipes to the world!

<br>

 **Tech Stack**
 - MongoDB for storing database entries
 - Mongoose as an Object Document Mapper
 - ExpressJS for server side
 - ReactJS to create the client side of the application
 - NodeJS is the environment in which the express server runs.
 - Passport as authentication middleware for Node
 - CSS and Bootstrap for frontend UI
 - Heroku for Server deployment 
 - Netlify for Client deployment
 - GitHub as a platform for version control 
 - Cypress for front-end testing
 - Figma, Balsamiq and Edraw Max for mood-boarding, wireframes and diagrams
 - CardboardIt for creating user stories in line with Agile
 - Trello as a Project Management Platform
 - Postman for testing HTTP requests

 ### R2 Data flow diagram

 ![Dataflow](./docs/DFD1.png)
 ![Keys](./docs/KEYDFD.png)
  
### R3 Application Architecture Diagram

![AAD](./docs/ARCHITECTURE-DIAGRAM.png)

SMOOTHIVERSE ARCHITECTURE DIAGRAM

The architecture of Smoothiverse are composed of frontend client, backend server and  a database management system.  The client makes a request to the server backend and the server fetches the data from the database that manages and stores data of Smoothiverse. The server backend is responsible for retrieving the information from the database and sends the results back to the client frontend. 

Here below is a brief description of the functions of each application;

REACT -  It is a Javascript library which can help to build user interfaces.
 
AXIOS -  Is a Javascript library that helps us perform asynchronous HTTP requests like GET or POST. It can be used from the front-end to gather data from the backend
 
NODE - It is an environment outside of the browser where we can run server side apps in Javascript . Node JS and NPM (Node Package Manager) are installed for the Express environment to run.
 
EXPRESS - It is a Node.js framework that simplifies the task of writing server-side code in web applications and encourages code reusability. Routing in express is the response of an application to an endpoint requested by the client, which is a path and an HTTP request. 
 
MongoDB - Is the database that records and stores the data. 
 
The user from the client side will need to sign up to access more functionalities such as Create/Update/Delete/Search a smoothie recipe. 

<br>
### R4 User Stories
These are very brief, informal descriptions of the requirements of the website from the user’s point of view. They are usually written in the “As a 'type of' user, I want 'a feature' so that 'reason' format."
These User stories were created on 'CardboardIt' by using cards of different colours for the types of users.
We wrote user stories to get an idea of what features to develop in the app and to show refinements in the user stories that happen in the process of building the app

![version1](./docs/version1.png)

![revised-version](./docs/revised-version.png)