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
       Ans:  Error-handling middleware always takes four arguments. You must provide four arguments to identify it as an                  error-handling middleware function. Even if you don’t need to use the next object, you must specify it to                      maintain the signature. Otherwise, the next object will be interpreted as regular middleware and will fail to                   handle errors.

             app.use(function (err, req, res, next) {
              console.error(err.stack)
              res.status(500).send('Something broke!')
             })

30. What is Object destructuring?

       [a,b] = [10,20];
       output- a=10; b=20;

       [a,b, ...rest] = [10, 20, 30, 40, 50];
              a=10; b=20; c= [30,40,50];

       {a,b} = {a:10, b:20}
                a = 10
                b = 20
       {a,b, ...c} = {a:10, b:20, c:30, d:40, e:50};
              a = 10
              b = 20
              c = {c:30, d:40, e:50}

31. What is shallow and deep copy and we can implement it?

       a) Shallow Copy: Object.aasing({}, obj);
              nested object value is shareable but parent object value is not shareable.
       b) Spread Operator

       Deep Copy: JSON.parse(JSON.stringfy(obj));
              nested object value and parent object value bith are not shareable.

32) What is piping in stream or pipe operator in stream?
       Piping is a process in which we provide the output of one stream as the input to another stream. It is normally used to       get data from one stream and to pass the output of that stream to another stream. There is no limit on piping                  operations.
       
              const fs = require('fs');
              
              //creating a readable stream
              let readableStream = fs.createReadStream('input.txt');
              
              //creating a writable stream
              let writeableStream = fs.createWriteStream('output.txt');
              
              // Pipe the read and write operations
              // read input.txt and write data to output.txt
              readerStream.pipe(writerStream);

33) What is process.nextTick() and When we use process.nextTick ( ) ?
       
       When in Node JS, one iteration of the event loop is completed. This is known as a tick. process.nextTick() taking a           callback function which is executed after completing the current iteration/tick of the event loop.
       
              process.nextTick(() => {
                     console.log('excetuted after end of the single iteration on event loop');
              })
              console.log('called first');
              
              output-> called first
                     excetuted after end of the single iteration on event loop
       Uses:
       
       To cleanup unwanted resources.
       To allow users to handle errors.
       To try a request to run before starting the next iteration of event loop.
       Allow a callback to run after call stack and before next iteration of event loop.
       
 34) Function Declarations vs. Function Expressions?
 
       
       
       
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




# HTML CSS Questions

1) Block level element
       
        A block-level element always starts on a new line and takes up the full width available (stretches out to the          left and right as far as it can).

       The <div> element is a block-level element.
       Examples of block-level elements:

       <div>
       <h1> - <h6>
       <p>
       <form>
       <header>
       <footer>
       <section>
       
 2) Scope level element
 
        An inline element does not start on a new line and only takes up as much width as necessary.

       This is an inline <span> element inside a paragraph.

       Examples of inline elements:

       <span>
       <a>
       <img>
       
