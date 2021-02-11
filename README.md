# React-Task-Tracker

I used JSON server that allows us to create a mock REST API server for storing the data:

https://www.npmjs.com/package/json-server

Installation:

1) ➡️ npm i json-server

2) At package.json:

    ...
    
    "scripts": {
    
          ...

          "eject": "react-scripts eject",

          "server": "json-server --watch db.json --port 5000"	//<- ADD THIS LINE
      
    }

3) Once everything it's on:

    ➡️ npm run server	  //create or load db.json
  
    ➡️ npm start        //at a new terminal

## Preview:

<p float="left">
  <img src="https://github.com/sergiornelas/React-Task-Tracker/blob/main/readme-images/1.jpeg" width="36%" height="36%">
  <img src="https://github.com/sergiornelas/React-Task-Tracker/blob/main/readme-images/2.jpeg" width="36%" height="36%">
</p>
