# K-Panel

K-Panel Uses Node.JS with ReactJS and MySQL for managing php based websites. This project has started to create a feature rich alternative to php based panel like c-panel with some of the basic functionalities to manage the website. It provide support of nginx, php-fpm and MySQL server stack. Some of the features to include

  - Management of multiple domain with a url relative to home route
  - FTP connection to upload files
  - PhpMyAdmin for management of databases
  - MySQL wizard for creation of users and databases and managing permissions.
  - Automated Script for Managing Wordpress Installations
  - A small CPU/Memory/IO widget
  - Backup using zip file and .SQL export

### Tech

K-Panel uses a number of open source projects to work properly:

* [ReactJS] - HTML enhanced for web apps!
* [MariaDB] - Database to manage websites data and the app itself
* [node.js] - for backend and performing system callbacks
* [Express] - fast node.js network app framework
* [Bootstrap 4] - For UI development



### Installation

K-Panel requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd k-panel
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```

