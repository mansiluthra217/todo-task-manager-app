MERN Todo Application

this is a basic mern stack todo application that will help manage your tasks effectiently and will have features like craeting, updating, deketing, getting all tasks and getting a single task by id and creating multiple todos at the single tym.

--- TECH STACK ---

1. Backend - MongoDB, express.js, node.js
2. Frontend - React.js, Redux.js, & Tailwind CSS

install project:
npm install

--- BACKEND ---

1. add your connection string and db name to your environment variables
2. run the backend server with command:
   cd todo-backend
   npm start

3. backend server will be running on port you mention in your environment variables

API'S for testing in postman:
| GET: http:localhost:5000/ --- // defaults welcome routes |
| GET: http:localhost:5000/api/v1/todos-all --- // gets all todos |
| GET: http:localhost:5000/api/v1/todo/:id --- // get a single todo |
| POST: http:localhost:5000/api/v1/todo/new --- // create a new todo |
| POST: http:localhost:5000/api/v1/todos-many --- // create many todos |
| PUT: http:localhost:5000/api/v1/todo/:id --- // update a todo |
| DELETE: http:localhost:5000/api/v1/todo/:id --- // delete a todo |

after this, its made sure that your backend works well

--- FRONTEND ---

1. run the react app with command:
   cd todo-frontend
   npm start

2. your project will start to run at your local machine at port 3000(default for react app)
