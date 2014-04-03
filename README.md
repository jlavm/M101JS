M101JS
======

Course Mongodb for node.js developers

<h1>Prerequisites in Mac</h1>
<ul>
<li>Xcode</li>
<li>Command Line tools fo Xcode</li>
<li>Hombrew</li>
<li>Mongodb</li>
<li>Node</li>
</ul>

<h1>Homebrew  installation</h1>

ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

<h1>Xcode installation</h1>

https://itunes.apple.com/us/app/xcode/id497799835?mt=12

<h1>Mongodb installation</h1>
brew install mongodb

To enter in your mongo database type mongod to start the server and then in other window or tab type mongo

<h1>Node installation</h1>

brew install node

After this type node in your console and paste the following

var http = require('http');<br/>
http.createServer(function (req, res) {<br/>
  res.writeHead(200, {'Content-Type': 'text/plain'});<br/>
  res.end('Hello World\n');<br/>
}).listen(5000, "127.0.0.1");<br/>

In the browser type localhost:5000 and if the message Hello world appears we have already node working
