# Recipe App

 This app is a recipe app that creates and saves recipe made by users.

## Description

This app for recipes enables users to sign up and log in to their accounts, granting them access to browse recipes crafted by other users within the system. Additionally, users have the option to generate their own recipes using the create-recipe feature. Moreover, users can save recipes on the home page, ensuring they are stored in the saved-recipe section for convenient retrieval in the future.

## Features

- **Home Page**: Displays the current stored recipes in database that are created by users that loged in. Users can save a recipe displayed on home page.
- **Login/Register Page**: Register page if not registered, login page after registration. Users must register to perform actions such as create recipes and save recipes.
- **Create Recipe Page**: A page to create a recipe by submitting a form of name, ingredients, instrcutions, imageUrl, and cooking time.
- **Saved Recipes Page**: A page that displays the saved recipes from home page. Every user has their own saved recipes.

## Built with

- MongoDB
- Express
- React
- Node.js

## Getting Started

**Prerequities**: installed npm, yarn, node.js

**Not Deployed Version**
```bash
git clone https://github.com/shuxinweng/recipe-app.git
```

```bash
cd client
```

```bash
npm install
```

```bash
npm start
```

```
open another terminal
```

```bash
cd server
```

```bash
yarn start
```