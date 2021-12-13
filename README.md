# Deployed Project Link: https://taskmanager-lewislee.netlify.app/

# Task Manager 
> A task manager tool that allows users to organize their tasks. In one glance, users can view what tasks need to be done, what tasks need to be worked on, and where something is in a process. 

> Project by [Lewis Lee](https://github.com/rexiah23)

## Features
* Users can add their own custom task lists and indivdual tasks. 
* Users can easily drag and drop tasks and lists to change their order. 
* Users can delete task lists or individual tasks when they are no longer needed. 
* Users can edit task list titles. 
* Users can selected custom backgrounds. 


## Back End:
Navigate to 'backend @ 31e5410' folder to visit the backend github repo.
###Database Setup: 

(If needed install [Postgres](https://www.postgresql.org/))

In the terminal, run these commands: 
1. `psql`
2. `CREATE ROLE trello LOGIN SUPERUSER PASSWORD 'trello';`
3. `\q`
4. `CREATE DATABASE trello;`
5. `\q`

To start the backend:
1. Open terminal at the root backend repo (backend @ 31e5410).
2. Install dependencies with `npm install`.
3. Run this command to reset the database: `npm run db:reset`
4. Run this command to start the server: `npm start`
 
## Front End:
Navigate to 'frontend @ 892c13e' folder to visit the frontend github repo.

### Setup
In the terminal, run these commands:
1. Delete the .env file if you want to connect to the local server (by default is connected to heroku hosted server). 
2. Install dependencies with `npm install`.

To start the frontend: 
1. Run this command to start the server: `npm start`



Final Product
![Alt text](/docs/1.png)
![Alt text](/docs/2.png)
![Alt text](/docs/3.png)
![Alt text](/docs/4.png)
![Alt text](/docs/5.png)

Powered by: 

- [ReactJS](https://reactjs.org/)
- [NodeJS](https://nodejs.org/)
- [ExpressJS](http://expressjs.com/)
- [Material UI](https://mui.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [react-beautiful-dnd](https://www.npmjs.com/package/react-beautiful-dnd)
