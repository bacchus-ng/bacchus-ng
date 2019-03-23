
![Image of OpenBacchus](https://openbacchus.com/static/gent/production/images/bacchus.png)

# OpenBacchus: Next Gen.

OpenBacchus: Next Gen. is a complate re-write of the original OpenBacchus with the [PatternFly](http://patternfly.org/) framework. 


## Installation

Install project node modules:

``` bash
npm i
```

### For Development

For development with [BrowserSync](https://www.browsersync.io/) run:
```
npm start
```

This will do two things:

1. It will build the static assets in the [dist](dist) directory. You can just click on the `dist/index.html` file to browse around.
2. It will automatically open up the running application in your default browser, which is located at `localhost:3000`.

### For Production
For production, you will just want to compile your webpack bundle. You'd then have to choose how to run your app (e.g. with Node by running `node server/app.js`, setting up CI, a process monitor, etc.; serving static assets built in the `/dist` directory) depending on your needs.

```
npm run build:prod
```

The resulting build will be in the [dist](dist) folder.
