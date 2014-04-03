M101JS
======

Course Mongodb for node.js developers

#Prerequisites in Mac

>Xcode
>Command Line tools fo Xcode
>Hombrew
>Mongodb
>Node

#Homebrew  installation

ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

#Xcode installation

https://itunes.apple.com/us/app/xcode/id497799835?mt=12

#Mongodb installation
brew install mongodb

To enter in your mongo database type mongod to start the server and then in other window or tab type mongo

#Node installation

brew install node

After this type node in your console and paste the following

var http = require('http');
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World\n');
}).listen(5000, "127.0.0.1");

In the browser type localhost:5000 and if the message Hello world appears we have already node working
