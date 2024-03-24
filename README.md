# Installing this to do list app

This project was bootstrapped with [Create React App].

-- first of all, download this Todo folder

-- inside there is the api foder,
     --todo is the frontend 
     --api is the backend
     NB// the sql database is inside the api folder. im gonna explain on how to install it

--- ill expect once you download this file you create aanother folder , sat TodList inside put todo and api folders separately
## Steps to set up

-once  you have the project downloaded on your local pc
1. cd todo, then run npm install in order to install all the dependencies
2. open another termoinal instance and run cd api, then run npm install to install backend dependencies.

## Database installatiom
On this particular project, i used the xampp server. so im gonna guide you on xampp server, however, if youy are using any other server that is sql formatted, you can run the todo.sql freely on it.

  --on xampp sever
  beforhand, create a database todo.
  1. navigate to import andselect it
  2. tap import a file and youll find the file on this path once inside the TOdo-List folder /api/db/
  3. import the file and the database will be set up

### `npm start`

youll need to have two instances of terminals, on poininting to api while the other to todo

run npm start on both terminal instances

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
