# Express Middleware Notes
![https://link](https://images.unsplash.com/photo-1610457642191-05328cdf34ff?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=750&q=80)
### What is a middleware?

Are functions that are executed during the HTTP request-response cycle or at any specific stage. 

### What are middleware useful for?
Let us integrate additional capabilities to the workflow such as **loggin** and **authentication**.

### The `next` function
The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.



[Express JS Middleware Docs](https://expressjs.com/en/guide/writing-middleware.html)

```
var express = require('express')
var app = express();

app.get('/', function(req, res, next)){
    next();
}
app.listen(3000);
```
## Best practices

- Add response and request validators functions in the middleware
