# Node-NPM-Assignment

1: What is the Event loop ?
Ans: Event loop is what allows JavaScript to perform asynchronous operations or call back function in a FIFO Ideology.

2: Explain the 6 phases of the event loop
Ans: 
1) Timers: This is where any timers are complected
2,3 ) Pending and Idle, Prepare: This phase executes internal activities on any callbacks
4) Polling: This is where all input/output callbacks (read&write.File, Server calls etc...) are processed
5) Checks: This is where all setImmediate timers as part of the input/output are executed
6) Close: This checks if all callbacks has been processed and if they are, then the process ends.