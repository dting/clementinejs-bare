### Bare Boilerplate

[Clementine.js Standard Repo](https://github.com/johnstonbl01/clementinejs) | [Clementine.js Bare Repo](https://github.com/johnstonbl01/clementinejs-bare) | [Clementine.js Beginner Repo](https://github.com/johnstonbl01/clementinejs-beginner)

#### Overview

Clementine.js is a lightweight MEAN stack boilerplate. In addition to MongoDB, Express, AngularJS and Node.js, Clementine.js uses Jade, Mongoose, Gulp, Bower and Sass. The purpose of this boilerplate is to offer a lightweight alternative to other boilerplates. This version of Clementine.js is stripped down to only include the essentials, and a small app template.

If you're just learning how to code, I suggest checking out the beginner version of Clementine.js. 

If you're looking for a demonstration of these technologies for a simple website, check out the standard version of Clementine.js.

#### Documentation

Full documentation about the bare version of the Clementine.js boilerplate [can be found here](http://johnstonbl01.github.io/clementinejs). 

#### Installation

Installation of the boilerplate has two prerequisites: Node.js / NPM and MongoDB. The instructions for these are detailed below, followed by installation instructions for Clementine.js.

##### Node.js & NPM

_Note:_ The Node insallation installs both Node & NPM.

**MAC OSX & Windows**

Head to the [Node.js install page](https://nodejs.org/download/). Download the appropriate file follow the installation instructions.

**Linux**

_Option 1_ - Install via PPA
```
$ sudo add-apt-repository ppa:chris-lea/node.js
$ sudo apt-get update
$ sudo apt-get install nodejs
```

_Option 2_ - Install via LinuxBrew

First, ensure [LinuxBrew](http://brew.sh/linuxbrew/) is installed. Then, enter the below into the Linux terminal:
```
$ brew install node
```

##### MongoDB

MongoDB has great installation instructutions for MAC OSX, Windows and Linux. [See this page.](http://docs.mongodb.org/manual/installation/)

##### Clementine.js

To install the boilerplate, first create a new directory for your project and cd into that directory from the terminal. Then type:

```bash
$ npm install clementinejs-bare
$ cd clementinejs-bare
$ npm install
$ bower install
```

##### Starting the App

To start the app, make sure you're in the project directory and type `gulp` into the terminal. This will start the Node server and connect to MongoDB.

You should the following messages within the terminal window:
```
MongoDB successfully connected on port 27017.
Node.js listening on port 3000...
```
Next, open your browser and enter `http://localhost:3000/`. Congrats, you're up and running!

## License

MIT License. [Click here for more information.](LICENSE.md)