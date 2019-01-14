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

**Implement this endpoint**

Basically already implemented!

* POST /login **PUBLIC**


**Do not actually implement these endpoints, just the routes and the authorization / middleware!**

## users 

* POST /user **PUBLIC** (basically, sign up)
* GET /user/:id **PUBLIC**
* PUT /user/:id **PRIVATE** (only user who is signed in can update his/her data)
* DELETE /user/:id **PRIVATE** (only user who is signed in can delete his/her data)

## posts

* POST /post **PRIVATE** 
* GET /post/:id **PUBLIC**
* PUT /post/:id **PRIVATE** 
* DELETE /post/:id **PRIVATE** 


