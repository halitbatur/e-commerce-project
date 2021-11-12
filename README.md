# curriculum-backend-e-commerce-project

## Instructions

### Collaboration requirements

Please don't split the code. Write every line of code together. In each group, every person should understand every line of code.

### Code

In this project, you will be using MongoDB, Mongoose, Express, JS in order to create an e-commerce backend app.

### Functional requirements

These requirements will basically update each version and you will add to the work you did the previous version so make sure you write clean code, also, this is why you see requirements titled Version N.

#### Version 1 requirements
In this version we will have our project setup and database running so we can start querying and manipulate data.
- Create a NodeJS project by creating a new folder and adding a file called `index.js` and `package.json` in it.
- Have MongoDB server running on your computer and ready, after that, create a Database in MongoDB and call it `e-commerce-app`.
- Back in your app folder, create a folder for setting up your DB connection, inside it put your DB connection file (so we can have a clean file structure).
- To establish the Database connection, we will need to install Mongoose and put the connection code in the connection file.
- Import some dummy data into your DB, you can use the cmd for that or MongoDB Compass.
- Setup Express-js and body-parser and start the server and test your DB connection with a simple get request.
- Having your initial app working, now it is time to work on our Model, create a `models` folder inside your app directory, and add a new model called `ShopItem`.
- Using Mongoose, create the schema for your ShopItem, it has to include the following:
  - title
  - image
  - price
  - description
  - seller: you should another Model for the seller and embed the seller inside the ShopItem.
  - genre

<b>For the data types and other validation criterias like required, length, you have to add them yourselves. For the seller Model, you also have to estimate what are the proporties for it.</b>
- After having the Models done, it is time to create a controllers folder and add `ShopItem` controller file to put our controllers there.
- Add a request to get all the shop items and return them as a JSON, if no shop item is available return a message to tell the user that.  
  
  
  
