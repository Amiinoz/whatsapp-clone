# WhatsApp Clone

Building WhatsApp clone with MERN Stack 🥞 (client, server, database).

With the following features:

* People can send a message
* People can see all the message that have been posted

<!-- ![example-site](example-site.gif) -->

## Objectives

* [] ⌨️ Get user input on the Client
* [] ⌨️ Get user input on the Client
* [] ⌨️ Get user input on the Client



<!-- ------------------- -->
<!--
* [x] 📝 Diagram the Full Stack
* [x] 🔎 Differentiate between Client and Server
* [x] ⌨️ Get user input on the Client
* [*] ➡️ Send user input from the client with fetch to the server
* [*] 🗃 Store data in a database
* [*] 🔍 Retrieve data from a database on the Server
* [*] ⬅️ Retrieve data from a server on the client using Fetch
* [*] 🙈 Hide/Show elements on the client
* [*] ✨ Add elements to the page on the client
* [] ✨ Page navigation and search
* [] 🚀 Deploy the client with now.sh
* [*] 🚀 Deploy the database with mlab
* [] 🚀 Deploy the server with now.sh -->

## Front-end
* [] Create React App
  * [x] npx create react-app whatsapp
* [ ]  Project starter wrap
  * [] Firebase
    * [x] Create a project
    * [x] Set up config (add app to start)
    * [x] Register app - next
    * [x] $ sudo npm install -g firebase-tools
    * [x] Clean up the app - del - test & header
    * [ ] Delete css file


<!-- --------------------------------- -->
<!--
* [x] Create client folder
* [x] Setup index.html
* [x] Bring in Skeleton CSS
  * http://getskeleton.com/
  * https://cdnjs.cloudflare.com/ajax/libs/skeleton/2.0.4/skeleton.min.css
* [x] Create Header
* [x] Create form
  * [x] Name
  * [x] Chat room
  * [x] Content
  * [ ] Log In
* [*] Listen for form submit
* [x] Hide the form
* [x] Show loading spinner
* [x] Get data from form and log it
* ✅ Get user input on the Client
* ✅ Hide/Show elements on the client -->

## Back-end
<!--
* [*] Create server folder
* [*] npm init -y
* [*] npm install express morgan
* [*] Setup index.js
* [*] Add GET / route
* [*] Add POST /messages route
  * [ ] log out req.body -->

## Front-end
<!--
* [*] fetch POST /messages with form data
* [*] See the CORS error and revel in this moment
* ✅ Send user input from the client with fetch to the server -->

## Back-end
<!--
* [*] npm install cors
* [*] Make sure the server is receiving the data
* [*] Add JSON body parser middleware
* [ ] Validate name, content and topic
  * [*] Must be a string
  * [*] Cannot be empty
* [*] If not valid
  * [*] Error code 422
  * [*] Invalid messageP, must be logged in, contain name and content
* [*] Setup DB Connection
  * [*] npm install monk
  * [*] connect to db
  * [*] create document collection (messages)
* [*] If Valid
  * [*] Create messageP object with
    * [*] name, content, created_date
  * [*] Insert into DB
  * [*] Respond with created mew object
* ✅ Store data in a database -->

## Front-end

<!-- * [*] Log out created messages after POST request
* [*] Show the form
* [*] Hide loading spinner -->

## Back-end

<!-- * [*] GET /messages
  * [*] Respond with messages from DB
* ✅ Retrieve data from a database on the Server -->

## Front-end

<!-- * [ *] fetch GET /messages
  * [*] Iterate over array
  * [*] Append each to page
  * [*] Reverse before appending
  * [*] Show the form
  * [*] Hide loading spinner
* [*] fetch GET /messages after creating a messageP
* ✅ Retrieve data from a server on the client using Fetch
* ✅ Hide/Show elements on the client
* ✅ Add elements to the page on the client -->

## Back-end

<!-- * [*] npm install bad-words
* [*] Use filter before inserting into DB
* [*] npm install express-rate-limit
* [*] Limit to 1 request every 15 seconds -->

## Deploy

<!-- * ✅ Deploy server with now
  * [ ] Setup environment variables
    * [ ] Database connection
      * process.env.MONGO_URI
  * ✅ Show mlab
  * [ ] Deploy with environment variable
    * now -e MONGO_URI=@evolveUMs-
  * [ ] Add alias
* ✅ Deploy client folder with now
  * [ ] Set API_URL based on hostname -->

## Improvements
<!-- * [] Pagination
  * Server
    * [] Message endpoints
    * [] Skip and limit from query params
        * [] Defaults: skip - 0, limit - 7
        * [] Include total count in response
    * [] Sort messages by date -->

## What's next?

<!-- * Add comments/replies to a messageP
* User Accounts
  * Don't just have the user enter their name
  * Sign up/Login
* User Profiles
  - Only show messages from a given user
* Search messages
* Hashtags
* User @mentions
* Realtime feed of messages -->

## Credits
<!-- * Photo by Volodymyr Hryshchenko  at https://unsplash.com/photos/V5vqWC9gyEU -->
