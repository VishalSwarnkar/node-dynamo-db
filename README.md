## Nodejs RESTFul api with dynamo DB local

### Setup in local dev environment

`RUN npm install`

### Start rest api and db in docker container

`RUN docker-compose up -d`

### Create table in DB

`RUN npm run create-table`

### Insert value in the table

`RUN npm run load-data`

### Read the inserted value from DB

`RUN npm run read-data`
