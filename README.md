# Twitter back-end

##  Technology Stack :
- ul Testing tool = Postman
- ul AccessToken storage = Redis
- ul Users & Tweets DB = MongoDB
- ul API Server = Express.js

##  REST API :

- ul POST /users - registration { login, password, passwordConfirm }
- ul PUT /users - login { login, password }
- ul GET /tweets - get your tweets [AUTH]
- ul POST /tweets - post your tweet [AUTH] { text }

##  Running the server

    npm install
    npm start
