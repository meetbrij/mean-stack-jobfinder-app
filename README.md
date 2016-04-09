# MEAN JobFinder app

This project is a simple Job Database application developed using MEAN Stack (MongoDB, Ember, Angular and Node).

Dependencies
- node.js and npm
- [MongoDB](https://www.mongodb.org/)
- [Python](https://www.python.org/)
- [MEAN.js](http://meanjs.org/)
- Bower
- Grunt

## Getting Started

Install MongoDB and set it up as follows
- create folder mongodb/data/db and mongodb/log
- run the installation command inside mongodb/bin folder
- install MongoDB as a service - USE STANDARD WINDOWS CMD AS ADMINISTRATOR
```
mongod --directoryperdb --dbpath c:\mongodb\data\db --logpath c:\mongodb\log\mongodb.log --logappend --rest --install 
```

To start service
`
net start MongoDB
`

To stop service
`
net stop MongoDB
`

To remove service
`
c:\mongodb\bin\mongod.exe --remove
`

Basic mongodb commands
```
mongo \\starts mongodb
show dbs \\lists all dbs, mean_dev is the main db
use mean_dev
show collections \\lists all tables inside mean_dev
db.users.find();
db.articles.find().pretty();
```

Setting up dependencies
```
npm install -g bower
npm install -g grunt-cli
```

To get you started you need to download the repository, extract and copy the contents to your project folder and then install the project dependencies using the following command:
```
npm install
grunt
```

The above project was created by following the steps given in the tutorial at [Eduonix](https://www.udemy.com/learn-angularjs-development/)