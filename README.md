# Server of Task Application
## Getting Started
 - Run install:
      ````bash
      npm install
      ````
 - Create file .env at root folder, then open it up and set up:
      ````bash
      JWT_SECRET=yoursecretkey
      MONGO_URI=mongodb://user:pass@mongo-host/db-name?retryWrites=true
      ````
## Test
 - Run in local:
      ````bash
      npm run dev
      ````
 - Run in heroku:
      ````bash
      npm run start
      ````