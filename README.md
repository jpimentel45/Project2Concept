## Project2 (just initial testing we can delete once we actually start the project)
Documentation:
http://docs.sequelizejs.com/manual/migrations.html#the-sequelizerc-file
Installing CLI: npm install --save sequelize-cli

Bootstrapping
To create an empty project you will need to execute init command: $ npx sequelize-cli init

// edit config.json file and set correct database credentials and dialect.

//If database doesn't exists yet, just call db:create command. With proper access it will create that database for you.

Creating first Model (and Migration)

// after run npx sequelize-cli model:generate --name User --attributes firstName:string,lastName:string,email:string

// Creates a model file user in models folder
// Create a migration file with name like XXXXXXXXXXXXXX-create-user.js in migrations folder

stoped here until group meets to creat db info and project name
// Next: Running Migrations: npx sequelize-cli db:migrate
