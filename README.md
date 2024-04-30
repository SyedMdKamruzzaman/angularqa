# Angular Interview Questions and Answers
1. What is stream?
   - Streams are just a sequence of values over time.
2. What is an observable?
   - An Observable is a function that converts the ordinary stream of data into an Observable stream of data.
3. What is asynchoronous programming?
   - Asynchronous programming is a technique that enables your program to start a potentially long-running task and still be able to be responsive to other events while that task runs, rather than having to wait until that task has finished.
4. Asynchoronous vs Multithreading
   -  multithreading programming is all about concurrent execution of different functions. Async programming is about non-blocking execution between functions, and we can apply async with single-threaded or multithreaded programming. So, multithreading is one form of asynchronous programming.
5. concatMap - waits for the previous Observable to complete before creating the next one. 
6. switchMap - for any source item, completes the previous Observable and immediately creates the next one
7. What is the purpose of the pipe() function in RxJS?
  - The pipe() function in RxJS is used to chain multiple operators together, allowing you to apply a series of transformations to an Observable stream. The pipe() function takes one or more operator functions as arguments and returns a new Observable with the applied transformations.
