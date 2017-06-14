# meteor_todo_blaze
Todo tutorial on meteor (mongo, blaze)

This tutorial references : [official meteor-blaze tutorial](https://www.meteor.com/tutorials/blaze/creating-an-app)

It follows most of the instructions with the exception of changing `Meteor.userId()` to `this.userId` in `imports > api > tasks.js`. This facilitates testing of the task functions without stubbing a user. 

## Instructions
- To start application: meteor
- To start tests: meteor test --driver-package practicalmeteor:mocha
