To be able to start the project make sure the terminal folder is ...\HMJ_Tech\sjavs

We will need to install the depenandices here

To be able to run "npm run dev" we will need to use the following terminal command

npm install next react react-dom

With this we are able to use the "npm run dev" command

To run "npm run build" we will need another depenandice

use the following terminal command

npm install uuid

to run the playwright tests, use the following command

npx playwright test

be aware to run the test, have one terminal running npm run dev, so that the website is hosted on localhost:3000
or else the test will fail.


## ⚠️ Important Notice

This project was developed as a prototype and depends on external services (Supabase and Clerk) that are no longer active.

Because of this:
- The full application may not run correctly without reconfiguration
- Database and authentication features are not functional

However:
- The core game logic and frontend structure remain intact
- The included documentation provides a full overview of the system design and functionality