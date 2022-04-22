This project demonstrates use of React.js and Node.js server to display tweet stream for perticular keywords.

## Structure

### Server

`server` folder contains a Node.js server. It reads tweets from Twitter's Streaming API and publishes them via Socket.io.

### Client

`client` folder contains a React.js application which displays tweets.

## Running

 - Create `config.json` file in server and put Twitter's Application Credentials there.
 - Do `npm install` in both client and server.
 - Run the server using `node index.js`
 - Run client in seperate terminal using `npm start`

## Technologies Used

 - **React** - frontend
 - **Bootstrap** - frontend design
 - **React-Redux** - For managing state
 - **Socket.io** - For streaming tweets from server
