# Pursuit Reddit

Let's reimplement Reddit API with express.

## High level requirements

### 1. Body Parser to handle JSON payloads in POST, PUT, DELETE requests
### 2. Logging service that drops messages to a logfile

Should write to `logfile.txt` in the following format:
```
PUT - /post/:id
{
    "title": "test title",
    "content": "..."
}
Mon Jan 14 2019 17:37:05 GMT-0500 (Eastern Standard Time)
```

### 3. Protected endpoints that require authentication

## Endpoints

Do not actually implement these endpoints, just the routes and the authorization / middleware!

* POST /user
* GET /user/:id
* PUT /user/:id
* DELETE /user/:id
