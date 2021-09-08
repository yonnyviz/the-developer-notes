# Express Middleware Notes

- Middleware are functions that have access to the request(req), response(res), the next function during the request-response cycle.
- Middleware is extecuted in the period when a server recieves a request and when it sends a response.
- Express middleware has application-level, router-level and error handling functionality.
```
var app = express();

app.get('/', function(req, res, next)){
    next();
}
```
## Best practices

- Add response and request validators functions in the middleware.