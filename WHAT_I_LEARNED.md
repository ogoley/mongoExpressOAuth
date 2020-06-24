Created new project and cluster on mongoDB. 
Created a user with a username and password
Added the connection to the DB in index.js using the credentials above, should save them as a secret somewhere.
  In /config/db.js we use mongoose to connect to mongoDB very simply
Created a server with express with a signup route, (app.use(/user) makes it so all routes declared after this will be appended to /user)