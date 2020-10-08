# Personal Expense Manager
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app),
adding on to it express-mongoose server.

## General description
Expense management web app.
Node.js server serving React.Js app using es6 features(through Babel).
UI by [Ant Design](https://ant.design/).

## Production deployment / production-like env.
- In order to serve React app through the server uncomment specified line in server.js.

## Starting the server 
- Run `yarn start:server` (nodemon keeps the process alive).
- Create a user manually at the db and paste the token in App.js! since clientside missing user gen.
- Server loads slower than the client side on dev env so make sure the server loads then refresh page.

## Start
- Runs the app in the development mode.<br />
- Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

- The page will reload if you make edits.<br />
- You will also see any lint errors in the console.


## Roadmap
- Utilizing auth on clientside to allow multiple users(currently hardcoded token). 
- GetAllCategory aggregation route server side.
