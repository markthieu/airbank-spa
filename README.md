# airbank-spa

This is a single page application displaying a list of transactions. Backend is done using a PostgreSQL db, Prisma and GraphQL with Typescript. Frontend is using Nuxt/Vue.js framework with Tailwind CSS.

# Demo video

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/pELp2st1Dck/0.jpg)](http://www.youtube.com/watch?v=pELp2st1Dck)

# How to set up

Backend

1. Cd into the project, run ```npm install``` to install dependencies.
2. If you don't have one create a PostgreSQL DB, then connect to the db in .env file
3. In seed.ts make your the .csv files are in the correct folder
4. Run ```prisma migrate dev --name init``` and ```prisma seed``` if seeding wasn't done automatically on migration
5. Run ```npm run backend``` to start up the server

Frontend
1. Cd from project to 'spa-frontend'
2. Run ```npm install``` to install dependencies
3. Run ```npm run dev``` to run the frontend app
