# Mini Project: E-commerce API

## Instructions

### Collaboration requirements

Please don't split the code. Write every line of code together. In each group, every person should understand every line of code.

### Overview

In this project, you will be using Node, Express, MongoDB and Mongoose in order to create an e-commerce backend app. This app will have 2 types of users: admins of the shop and customers.

We will work through this project in versions. these versions will be as following:
1. E-commerce admin features
2. Customer features
3. Authentication
4. Tests
5. Deployment

We may add or remove few versions as we progress through the project during the bootcamp.

### Functional requirements

The requirements will update in each version and you will add to the work you did the in previous version so make sure you write clean code, also, this is why you see requirements titled as Version N.

**Attention**: All types of validation and error handling should be taken in-consideration in all requests.

#### Version 1 Requirements
In this version we will make sure everything is setup and working from the database to Express server and their connection. Then we will start working on all the admin features and requirements as following:
- First of all, you need to define your `shop-item` schema, it should at least have these fields (the data types and other validation criterias will be left for you to decide on):
  - title
  - image
  - price
  - description
  - availableCount 

Now, after setting up the model, let's start working on the requests.

_Note: admin routes start with `/admin`._

- The admin should be able to add new shop items.
- The admin should be able to update the details of a shop item, such as description, price, available count, etc.
- The admin can delete one or more items from the items list.
