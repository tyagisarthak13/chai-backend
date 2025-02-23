=> first do npm init - initialize a project and create the package.json file.
For Git -
a) git init - creates a new Git repository
b) git add . - adds / stages all of the files in the current directory
c) git commit -m "put message inside"

=> A .gitkeep file tells github to do the opposite of its default behaviour, which is to ignore empty folders.
=> If you want to track an empty folder, or a folder with untracked files, create a 0kb file with the .gitkeep file extension in that folder.

=> Environment variables in Node are used to store sensitive data such as passwords, API credentials, and other information that should not be written directly in code.

=> devDependencies are the packages a developer needs during development. These dependencies may be needed at some point during the development process, but not during production/execution.

=>Below are the files that contain actual programming & business logic. In production, it is recommended that these files & folders be created within a folder named src ( source) for segregation of files.

- server.js/app.js:- code written to run the server/app.
- index.js:- code written to connect servers, databases & API's.
- constant.js :- code written to create & manage some constant variables.
  => Besides files, we also need to create some folders named model, utils, middleware, db, route, and controller.
- DB:- code was written to make the database connection, whether the database is Mongo dB or MySQL.
- model:- code written to create a model & define structure to store data.
- middleware:- code written here which works between API request & controller. For eg. user verification.
- route:- all the route codes written here like "/login", "/post", "/sign".
- controller :- Actual core programming & business logic code written here.
- util:- code written which is used as utilities like email, uploading files.

=> The .prettierrc file is a configuration file used to define and customize Prettier's behavior in your project. These rules help maintain consistent code formatting across a project.

=> We mostly use app.use for middlewares and configuration.

=> bcrypt is a library that helps you hash password.

=> JWT (JSON Web Token) is a compact, secure way to transmit information between two parties as a JSON object. It is commonly used for authentication and authorization in web applications.

=> Pre middleware in Mongoose is allowed to execute custom logic before specific operations are performed on a model instance. These operations can include saving documents, validating data, or even removing documents.

=> Cookies are small pieces of data stored on the user's browser by a website. They help websites remember user information, preferences, and session details across visits.
