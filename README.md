# RecipEasy

## Intro

RecipEasy is a web application designed to help users manage their favorite recipes efficiently. The core feature of the application is a page scraper function that allows users to input a URL, retrieve the recipe, and save it to their profile.

The primary user interaction flow is as follows:
**Sign up -> Retrieve Recipe -> Edit Recipe -> View Recipe in Profile Page**

The application includes the following features:

- Users can create an account and login.
- Users can scrape online recipes from websites and food blogs and save them to their account.
- Users can edit their saved recipes.
- Users can create their own recipes.
- Users can access their saved recipes on their profile for easy access.


## TechStack
-MERN
-Tailwind

## Quick-Start

### Install NVM
1. Make sure you have node and NVM installed. 
```
brew install nvm
```
2. Install the latest version of [Node.js](https://nodejs.org/en/)

### Set up the project
1. Fork/Clone this repository.
2. Install dependencies for the 'frontend' & 'api' application: 

```
cd frontend
npm install

cd ../api
npm install
```

3. Install an ESLint plugin for your editor
4. Intall MongoDB if you don't have one on your computer

```
brew tap mongodb/brew
brew install mongodb-community@6.0
```
   _Note:_ If you see a message that says
   `If you need to have mongodb-community@6.0 first in your PATH, run:`, follow
   the instruction. Restart your terminal after this.

5. Start MongoDB

```
brew services start mongodb-community@6.0
```

### Set up environment variables

You need to create '.env' files for both the frontend and the api.

#### Frontend
Create a file 'frontend/.env` with the following:

```
VITE_BACKEND_URL="http://localhost:3000"
```

#### Backend
Create 'api/.env' with the following:

```
MONGODB_URL="mongodb://0.0.0.0/acebook"
NODE_ENV="development"
JWT_SECRET="secret"
```

### Running the server

1. In the api directory, run:
```
npm run dev
```
2. In the frontend, run:
```
npm run dev
```

