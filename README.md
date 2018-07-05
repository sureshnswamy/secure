


## Updating to New Releases

Create React App is divided into two packages:

* `create-react-app` is a global command-line utility that you use to create new projects.
* `react-scripts` is a development dependency in the generated projects (including this one).

You almost never need to update `create-react-app` itself: it delegates all the setup to `react-scripts`.

When you run `create-react-app`, it always creates the project with the latest version of `react-scripts` so you’ll get all the new features and improvements in newly created apps automatically.


In most cases bumping the `react-scripts` version in `package.json` and running `npm install` in this folder should be enough, but it’s good to consult the [changelog](https://github.com/facebookincubator/create-react-app/blob/master/CHANGELOG.md) for potential breaking changes.


## Folder Structure

After creation, your project should look like this:

```
secure/
  README.md
  client/
    node_modules/
    src/
      Auth/
        Auth.js
        auth0-variables.js
      components/
        Callback/
          Callback
          loading.svg
        About.js
        App.css
        App.js
        Contact.js
        Feed.js
        FeedItem.js
        Jumbotron.js
        routes.js
      history.js
      index.js
    package.json
  server
    node_modules/
    index.js
    package.json
   
```

For the project to build,

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.



In client directory, you can run:

### `npm run start`

Runs the React app <br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run start `

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](#running-tests) for more information.


Note that **the project use ES6 syntax)**:

