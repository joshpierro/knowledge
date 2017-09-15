# Kyle Simpson THIS Rules

1. was the function called with nthe new keyword, if so use that object 
2. Was the function called with call() or apply(), if so use the object passed to those functions
3. Was the function called via a containing/owning object(context) (like a function, try catch)
4. Default to global object
