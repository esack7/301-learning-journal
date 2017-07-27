# Day 12
## Code Fellows 301 Learning Journal

REST - Representational State Transfer

Server --> Verbs - GET, POST, PUT, DEL

GET /article
POST/article
PUT/article/:id
DEL/article/:id

$.ajax({
    url: 'api.github.com',
    method: 'GET',
    headers: {
        Authorization: 'token ********************************'
    }
}).then(console.log, console.error);
