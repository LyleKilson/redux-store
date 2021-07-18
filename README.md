<h1 align="center">Redux Store</h1>
<p align="center">State demonstration</p>

<p align="center">
    <img src="https://img.shields.io/github/repo-size/lylekilson/redux-store" />
    <img src="https://img.shields.io/github/issues/lylekilson/redux-store" />
    <img src="https://img.shields.io/github/last-commit/lylekilson/redux-store" >
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-red"  />
    <img src="https://img.shields.io/badge/mySQL-purple"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>

## Discrption
Redux Store is a refactor of the [E-Commerce](https://github.com/LyleKilson/e-commerce-back-end) application that uses Redux (Links to an external site.). This demonstration will show users how to manage global state using React’s Context API. The Context API is quickly gaining traction as a worthy alternative or perhaps even successor to other libraries that manage global state in tandem with React, such as Flux or MobX. Nonetheless, the open-source JavaScript library Redux remains the industry standard for managing complex state in a large-scale React application.
## User Story

The following is an example of a how a user would like to use this application:

```
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Application Functioanlity

The following is the funcatioanlity that the application will consist of based on the users requests mentioned above:

```
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Demo Videos

![demoVideo](./images/demo.gif)

Seeding and starting of the DB and server.

---

![demoVideo2](./images/GETall.gif)

`GET` routes returning all Categories, all Products, and all Tags being tested in Insomnia Core.

---

![demoVideo3](./images/GETbyID.gif)

`GET` routes to return a single Category, a single Product, and a single Tag being tested in Insomnia Core

---

Click this [link](https://drive.google.com/file/d/1NmMGa0ilBML55Q9gwJL5TepVixNS6f-Y/view) to see the full demo video on `POST`, `PUT`, and `DELETE` routes for Categories, Products, and Tags being tested in Insomnia Core.

---

## Installing Dependencies

Enter the following command to install the required Node Package Modules:

`npm i mysql2 sequelize dotenv`

## Running the Application

Enter the following command in your CLI at the root of the application

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`

`npm start`

## Contibutions

[Kyle Wilson](https://github.com/lylekilson)