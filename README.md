# create-receice-kata-user-postman

##Register POST https://blog.kata.academy/api/users
###Request:
{
  "user": {
    "username": "Fievel",
    "email": "pavelfilimonov@gmail.com",
    "password": "Fievel23"
  }
}

###Response:
{
    "user": {
        "username": "fievel",
        "email": "pavelfilimonov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZTRjZDU4NmY4YmVlMWIwMDU1MWVkZCIsInVzZXJuYW1lIjoiZmlldmVsIiwiZXhwIjoxNjgxMTIzMTYwLCJpYXQiOjE2NzU5MzkxNjB9.v2l6Ulw_Jshmih6B9uwEyvI9JHpCepB3XksCEKX7Kw0"
    }
}

##Authentication POST https://blog.kata.academy/api/users/login
###Request:
{
  "user": {
    "email": "pavelfilimonov@gmail.com",
    "password": "Fievel23"
  }
}

###Response:
{
    "user": {
        "username": "fievel",
        "email": "pavelfilimonov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZTRjZDU4NmY4YmVlMWIwMDU1MWVkZCIsInVzZXJuYW1lIjoiZmlldmVsIiwiZXhwIjoxNjgxMTI0MzI5LCJpYXQiOjE2NzU5NDAzMjl9.xdUEX3-x_3wlPQ4ohwVFjJwMn8RdUy8n3RddmPCgWJo"
    }
}

##Get current user GET https://blog.kata.academy/api/user
###Request: No parameters

###Response:
{
    "user": {
        "username": "fievel",
        "email": "pavelfilimonov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZTRjZDU4NmY4YmVlMWIwMDU1MWVkZCIsInVzZXJuYW1lIjoiZmlldmVsIiwiZXhwIjoxNjgxMTMwMDU4LCJpYXQiOjE2NzU5NDYwNTh9.F1wN2WfROICk4Z3D3MKSaLEVkh5qWbY1U2_8IoHv8vQ"
    }
}
