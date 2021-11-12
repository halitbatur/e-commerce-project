# curriculum-backend-e-commerce-project

## Instructions

### Collaboration requirements

Please don't split the code. Write every line of code together. In each group, every person should understand every line of code.

### Code

In this project, you will be using MongoDB, Mongoose, Express, JS in order to create an e-commerce backend app.

### Functional requirements

These requirements will update each version and you will add to the work you did the previous version so make sure you write clean code, also, this is why you see requirements titled Version N.

In general, we will split this project into 5 versions (maybe we add more while going through the project), these versions will be as following, admin features, customer features, authentication, tests, and deploy.

**Attention**: All types of validation and error handling should be taken in-consideration in all requests.

#### Version 1 requirements
In this version we will make sure everything is setup and working from Database, Express, and our connection, then we will start working on all the admin features and requirements as following:
- First of all, you need to define your Shop item schema, it should at least has these fields (the data types and other validation criterias will be left for you to decide on):
  - title
  - image
  - price
  - description
  - seller: you should have another Model for the seller and reference the seller inside the Shop item.
  - genre  

Now, after setting up models, let's start working on the requests.

_Note: admin routes start with `/admin`._
- The admin should be able to add new items.
- The admin should be able to update the content of a shop item.
- The admin can delete item or items from the items list.
