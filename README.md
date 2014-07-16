angularFirst
============

This is the first angular application created by me.

STEPS to start with:

1. Open GitBash and cd to project location
2. Make sure you have NPM, GRUNT, Bower and Yeoman installed. If not Install them.
3. run :
    `mkdir angularjs-grunt-example` //Create project directory
   
    `yo angular` //runs yeoman to get angular and other dependencies

The package.json file
Yeoman will generate a package.json file (similar to a Gemfile used in Ruby) which will list all project dependencies. 
To install these you can simply run npm install.

Run grunt karma

`grunt karma`

All tests pass!

Run grunt server
`grunt server`

** If you get a message like the one below--
Running "server" task
>> The `server` task has been deprecated. Use `grunt serve` to start a server.

run `grunt serve`

Read below :
http://tylerhenkel.com/creating-apps-with-angular-and-node-using-yeoman/
