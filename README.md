# Node-NPM-Assignment

1: What is the Event loop?
Ans: Event loop is what allows JavaScript to perform asynchronous operations or callback functions in a FIFO Ideology.

2: Explain the 6 phases of the event loop
Ans: 
1) Timers: This is where any timers are completed
2,3 ) Pending and Idle, Prepare: This phase executes internal activities on any callbacks
4) Polling: This is where all input/output callbacks (read&write.File, Server calls, etc...) are processed
5) Checks: This is where all setImmediate timers as part of the input/output are executed
6) Close: This checks if all callbacks have been processed and if they are, then the process ends.

3: List some best practices in server-side code development
Ans:
1) Place emphasis on the quality of the code.
2) It is recommended to prioritize the usage of ES6+ and Async/Await.
3) Keep Code Small
4) Handle errors
5) Test your code

4: What is NPM5: How do you initialize a package in npm
Ans: NPM5 is a version of the (NPM), a tool for managing project dependencies via the command line. It's also a website hosting platform for developers to publish and share reusable code packages for use in other projects. We use "$ npm init" in our terminal to initialize package in npm.

5: How do you run a script in the package.json?
Ans: You run a script in the package.json by initializing $ npm run (argument). The argument is the name of the script e.g $ npm run prettier