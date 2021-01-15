# APIAssignment
# Assignment 2 - Web API.

Name: Dara O'Sullivan

## Features.


## Installation Requirements

Node, NPM, MongoDB.  


## API Configuration

```bat
NODE_ENV=development
PORT=8080
HOST=_yourhost 
TMDB_KEY=_key
mongoDB=_mongodb
MONGO_DB=_mongodb
SEED_DB=true
SECRET=_yoursecret
```


## API Design

|  |  GET | POST | PUT | DELETE
| -- | -- | -- | -- | -- 
| /api/users Gets a list of users
| ... | ... | ... | ... | ...


## Security and Authentication
All routes are connected with login of username and password. 

## Integrating with React App

~~~Javascript
export const getMovies = () => {
  return fetch(
     '/api/movies',{headers: {
       'Authorization': window.localStorage.getItem('token')
    }
  }
  )
    .then(res => res.json())
    .then(json => {return json.results;});
};

~~~

## Extra features
 

## Independent learning.


