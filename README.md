# **Goodreads-Book-Search**

This application uses goodreads api to look for books by title, author or isbn code.

This project was bootstrapped with `create-react-app` and deployed live at https://goodreads-react.herokuapp.com/

# Running the application locally

**Prerequisites:** You need to have Node + NPM installed.

**Required Environment Variables:**

`REACT_APP_API_KEY` : Goodreads API Key you can get from [here](https://www.goodreads.com/api/keys).

Save it in the `.env` file as described [here](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-custom-environment-variables)

Having done that, here is how to run the application locally in development mode.

**Clone the repo:**

    git clone https://github.com/sharmaaayush1989/goodreads-react

**Install dependencies:**

    npm install

**Starting the application in development mode:**

    npm start

# Building the application:

To build the production assets, run

    npm run build

# Testing the App:

Right now there is only one test suite. (renders without crashing)

    npm test

# Features In Current Version:

1. Search for books by title, author, or ISBN.
2. Displays upto 20 search results in bootstrap cards.
3. Displays only title, author, and link to goodreads page.
4. See the description and rating, and other details by clicking on individual result.

# Future Implementation:

Yet to be decided. 
