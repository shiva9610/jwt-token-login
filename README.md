# jwt-token-login
NodeJS rest Api authentication with JWT tokens

# Clone this App

Do NPM INSTALL

# IN db.js
Change your monog db connection

# Start your project
node server.js

# Use Any tools like postman 
 For Register: You need to post your name, email and password on /api/auth/register url. it will generate JWT token for every register users, it will be used during login time
 
 For Login: you need to put email and password with headers e.g: x-access-token: <generated tokens>
