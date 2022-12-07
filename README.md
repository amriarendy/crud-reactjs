### crud-reactjs

- import nodejs_database.sql in mysql database
- how to running backend
  - open terminal `cd backend`
  - backend `node app` or `nodemon app`
- how to running frontend
  - open terminal `cd frontend`
  - frontend `npm start`

### info

- node@16.16.0
- npm@8.11.0

### backend node modules

```json
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^4.18.2",
    "mysql2": "^2.3.3",
    "sequelize": "^6.26.0"
}
```

### frontend node modules

```json
  "dependencies": {
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "axios": "^1.2.1",
    "bulma": "^0.9.4",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.4.4",
    "react-scripts": "5.0.1",
    "web-vitals": "^2.1.4"
  }
```

### database

- mysql

### how to running

- cd backend

  - node app.js or nodemon app
  - use port 5000

- cd frontend
  - npm start
  - port 3000

### url data

- get all data users

  - method: GET
  - http://localhost:5000/users

- get data users by id

  - method: GET
  - http://localhost:5000/users/id

- create data users

  - method: POST
  - http://localhost:5000/users

- update data users by id

  - method: PATCH
  - http://localhost:5000/users/id

- delete data users by id
  - method: DELETE
  - http://localhost:5000/users/id
