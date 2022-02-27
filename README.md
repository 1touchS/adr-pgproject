# Full Stack Web Application 

A full stack web application using the following guidelines: 

1. Typescript for both frontend & backend
2. Backend using: 
  - ExpressJS w/ Typescript
  - TypeORM
  - Postgres DB
3. Frontend using: 
  - Angular 8 
  - Typescript

## Approach

I've taken a full stack approach and focused on the following:

### Stack:
- Angular (FE)
- Express (Node.js) Backend
- Postgres

### Build Environment
- Used Docker to build a demo stack with the technologies defined above.

### Front-End
Added buttons / function to edit/add/delete employees

Added Modal / Form Component for add/edit

#### Future Considerations:
  - Add buttons/pages to authenticate users to login
  before making changes to the app

### Database
Use `Postgres` as the tool of choice because of personal preference.
  - Can be easily swapped out for any DB
  - Used TypeORM CLI for migrations of DB tables.

#### Future Considerations:
  - Add replication / caching if application size grows.

### Extras

- Used `editorconfig` & `prettier` for standardized formatting
- Used `gitflow` process for merging and development

#### Future Considerations:
  - Add CI/CD build tools

### Start your engines

Run the stack by using the following command

```
$ npm start
```

Once the containers are up and running.

1. Navigate to `http://localhost:8000` for the front-end
2. Navigate to `https://localhost:4200` for the backend

