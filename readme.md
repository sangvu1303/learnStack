### NodeJs(Express):

    npm init

    npm install --save body-parser@1.20.2 dotenv@10.0.0 ejs@3.1.9 express@4.18.2

    npm install --save-dev @babel/core@7.15.5 @babel/preset-env@7.15.6 @babel/node@7.15.4 nodemon@3.0.1

### MySql(Sequelize):

    npm install --save-dev sequelize@6.33.0 sequelize-cli@6.6.1

    npm i mysql2

    cd src

    npx sequelize-cli init

    npx sequelize-cli db:migrate

> > example:

    npx sequelize-cli model:generate --name User --attributes email:string,firstName:string,lastName:string,address:string,gender:boolean,roleid:string --> change file user.js --> create all file models & migration --> copy & paste code

    npx sequelize-cli db:migrate // it is code what create database in mysql

    npx sequelize-cli seed:generate --name demo-user // create fake database for test

    npx sequelize-cli db:seed:all

### Git

    git init

    git add .

    git commit -m '....'

    git remote add stack git@github.com:{yourAccount}/{yourProjectName}.git

    git push stack master
