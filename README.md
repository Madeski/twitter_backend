# Twitter back-end

##h1 Technology Stack :
*Testing tool = Postman
*AccessToken storage = Redis
*Users & Tweets DB = MongoDB
*API Server = Express.js

##h1 REST API :

*POST /users - registration { login, password, passwordConfirm }
*PUT /users - login { login, password }
*GET /tweets - get your tweets [AUTH]
*POST /tweets - post your tweet [AUTH] { text }

##h3 Running the server

    npm install
    npm start
