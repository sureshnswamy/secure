


## Securing React App with Auth0

# server 

This demo use simple `express` routing enabled with `cors` a middleware for the server/api. Express-jwt middleware to authenticate HTTP requests using JWT tokens.  

Also `jwks-rsa`, a library to retrieve RSA (Rivest–Shamir–Adleman) is one of the first public-key cryptosystems) signing keys from a JWKS (JSON Web Key Set) endpoint. And to validate a JWTs scope to authorize access to an endpoint `express-jwt-authz` is used.

to start the server 

`npm start`
ther server set to run in port 4000 [http://localhost:4000](http://localhost:4000).

# client

In client directory, you can run:

`npm start`

Runs the React app <br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


## Folder Structure

After creation, your project should look like this:

```
secure/
  |
  README.md
  |
  client/
    |   
    node_modules/
    |
    public/
      index.html
    |
    src/
      |
      Auth/
        Auth.js
        auth0-variables.js
      |        
      components/
        |
        Callback/
          Callback
          loading.svg
        |
        About.js
        App.css
        App.js
        Contact.js
        Feed.js
        FeedItem.js
        Jumbotron.js
        routes.js
      |
      history.js
      index.js
    |
    package.json
  |
  server
    |
    node_modules/
    index.js
    package.json
   
```

For the project to build,

* `public/index.html` is the page template;

For both client and server 
* `src/index.js` is the JavaScript entry point.



Note that this project use **ES6 syntax**

