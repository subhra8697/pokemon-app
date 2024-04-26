<h1 align="center">Pokedex React App</h1>
The Pokemons App is an interactive platform where users can explore and interact with their favorite Pokemon characters. It offers various features such as searching and filtering Pokemon, playing the original Pokemon OST, making Pokemons dance, favoriting Pokemon, and viewing detailed stats.

## Getting Started
To use the Pokemons App, follow these steps:

  1. Go to the SignUp page and create a new account.
  2. Once logged in, you'll be directed to the main page where you can explore various features.

## Technologies Used
- Frontend: React.js, Recharts.js
- Backend: Node.js
- Database: MongoDB Altlas


## How to Run the project

1. Make sure you have Node.js and Git installed.

2. Clone this repo from your command line.

3. Navigate into the `./server` directory and run the command `npm install`

4. Create a new file in the public project directory and call it `.env`. 

5. Connect your project to the database:
- Create a MongoDB Atlas account at https://mongodb.com
- Connect your project to the MongoDB Cluster by clicking on the "connect" button, choosing the "connect to your application" option and copying the link.

Sample .env:

```
DB_STRING="mongodb+srv://.........."
PORT=8081
SESSION_SECRET="Very strong password"
```

7. Run `nodemon` on your cmd. Your backend server will be running on port 8081.

8. Open another cmd, navigate into the `./react-app` directory and run the command `npm install`

9. Run the command `npm start` on your cmd.

10. Go to http://localhost:3000/ on your browser.

## Debugging
If you get a CORS error when making requests to the backend server:
- make sure to include https://localhost:3000 in the `whitelist` array in `./backend/server.js`
- change the `secure` attribute to `false` in the session obj in in `./backend/server.js`


## How to use main features

### Pokemons
- Go to the SignUp page and create a new account
- Filter or search pokemons by typing on the search input or clicking the filter checkboxes
- Play pokemon OST, change the volume, switch songs through the media player on top
- Make pokemons dance throught the 'Everybody Dance' button
- Favorite pokemons by clicking on the star inside a pokemon's card
- Expand pokemons to see their stats by clicking on the cards

### Admin Dashboard
- Make yourself an admin by changing the `isAdmin` property to true on your user document (in MongoDB Atlas)
- click on the 'Dashboard' option on the navbar
- See multiple stats pertaining to your project (Top Users, Most recent errors, etc)



