Net-Friends

Net-Friends is a web application that allows users to create an account, upload images, and log in using their credentials. The application is powered by a MongoDB database for data storage and user account management.

..........  Server Side Setup  ..........

cd server

npm install

Create a .env file if not already present and add:

MONGO_URL='mongodb+srv://daqiqparwiz:4o1KZ8Rq3TM2YEIF@cluster0.fwngm.mongodb.net/social?retryWrites=true&w=majority&appName=Cluster0'

JWT_SECRET='somesuperhardstringtoguess'

PORT=3001

node index.js

..........  Client Side Setup  ..........

cd client

npm install

npm start

Running the Application

Ensure both the server and client are running to access the full functionality of the application.

