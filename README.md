# js-notes

# NODE.JS Questions

1. Brief about latest project done in nodejs?

2. What will be the latest version of node.js and what will be the updated features?

3. Event loop timer in nodejs & how it works? (Giving some example)

4. setTimeout() & how it works? (Giving some example)

5. How async await work in nodejs?

6. How to do multiple async call parallel in nodejs?

7. How to execute cron_job with using cluster in nodejs?

8. Diff between const, let, var?(Giving some example)

9. What is closure in nodejs?

10. What is lean in MongoDb?

1. previous project description

2. project related question

3. jwt token

4. how event loop work?

5. node is single threaded or multiple threaded?

6. promise and asynch/await

7. cache in nodejs (working)

8. ES6 features

9. Diffrence between arrow and normal function.

10. Diffrence between call, apply and bind with example.

11. Diffrence between Object.create() and new Object().

12. Object.seal and freeze diffrence?

13. what is deep and shallow copy in JS?

14. Promise.all, Promise.race ?

15. Async and Sync API?

16. Hoisting and its uses?

17. stream and buffer in Nodejs.

18. pipe in stream?

19. What is IIFE?

20. How to execute multiple async function parallel?

21. How to handle 10000 request concurrently in nodejs using single thread.

22. What is socket.io and how to use it and its mechanism, also create socket event.?

23. Callback hell and Promises?

24. app.js and package.json file?

25. what does scripts define in package.json?

26. What is middleware and how to define custom middleware?

27. What is aaplication level middleware, route level middleware and 

28. What is next() in nodejs?

29. what is Error-handling middleware
       Ans:    Error-handling middleware always takes four arguments. You must provide four arguments to identify it as an  error-handling middleware function. Even if you don’t need to use the next object, you must specify it to maintain the signature. Otherwise, the next object will be interpreted as regular middleware and will fail to handle errors.
      
      app.use(function (err, req, res, next) {
  console.error(err.stack)
  res.status(500).send('Something broke!')
})

30. What is Object destructuring?

31. What is shallow and deep copy and we can implement it?

# ANGULAR.JS Questions

1. What is Component?

2. What is Directive? Its Uses

3. Types of Directive?

4. Custom Directive

5. Diffrence Component and Directive.

6. What is pipe and its uses?

7. Custome Pipe creation.

8. Angular Life cycle

9. Explain ngOnInit, ngOnChange, ngAfterViewInit, ngDoChange, ngAfterContentInit

10. What are Guards?

11. What is AuthGuard, Resolver and ActivateChild and its uses?

12. What is ViewEncapsulations?

13. Interaction between Components Sibling, Parent to Child, Child to Parent?

14. What is EventEmitter?

15. main.ts file, package.json, angular.json, tsconfig.ts file explanation?

16. What is bootstraping ?

17. Angular PWA and SSR explanation?
