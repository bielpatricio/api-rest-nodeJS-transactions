<div id="top"></div>

<!-- PROJECT LOGO -->

<br />
<div align="center">
  <h1 align="center">Project to learn how do tests</h3>
</div>

<!-- TABLE OF CONTENTS -->

## Contents

<p align="center">
    <p><a href="#about-the-project" title=" go to About the Project">About The Project</a></p>
    <p><a href="#running-locally" title=" go to Running locally">Running locally</a></p>
    <p><a href="#routes" title=" go to Routes">Routes</a></p>
    <p><a href="#contact" title=" go to Contact">Contact</a></p>
  </p>

<br>
<!-- ABOUT THE PROJECT -->

# About The Project

This project was created to learn about NodeJS fundamentals and tests, how create routes, a database and the concept of streams, create tests.

<br>

# Running locally

```bash
# Clone this repository
$ git clone https://github.com/bielpatricio/api-rest-nodeJS-transactions
# Access the project folder in your terminal
$ cd api-rest-nodeJS-transactions
# Install the dependencies
$ npm i
# Run the application in development mode
$ npm run dev
# The application will runing on port 3333, so you can access the url http://localhost:3333/ to do the requests.
# Run the tests
$ npm test
```

# Routes

For the project, 4 routes were created:
   
    1. List all the users in the database
      -> `http://localhost:3333/transactions`, (GET)
    
    2. Get order by id, which will get the details of a specific order 
      -> `http://localhost:3333/transactions/12`, (GET)
    
    3. Create order, which will create a new order 
      -> `http://localhost:3333/transactions`, (POST)
      
      3.1 body ->
      
      {
          "title": "teste 4",
          "amount": 2000,
          "type": "credit" // "debit"
      }
  
    4. Get a sumary of all your transactions
      -> `http://localhost:3333/transactions/summary`, (GET)

# Contact

Gabriel Patrício - gabrieltp087@gmail.com - [https://github.com/bielpatricio/](https://github.com/bielpatricio)

<p align="right">(<a href="#top">back to top</a>)</p>
