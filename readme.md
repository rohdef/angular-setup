# Angular setup project

This project exists to create a fast setup for a reasonably simple
angularjs setup.  It leans up against the
[https://docs.angularjs.org/tutorial](angular tutorial).

The setup creates a basic template for haivng an angular app that uses
bower repositories for front end dependencies. It uses karma for
automatically running unit tests and protractor for end to end tests.

All can be run using the npm commands and the only dependency is
[https://nodejs.org/en/](nodejs) and npm, just as the angularjs
tutorial.

## Commands
Currently the following commands are supported

    # Install the dependencies, including the bower ones
    npm install

    # Run a simple http server for testing (especially relevant for AJAX calls)
    npm start

    # Run karma in the background so it runs the tests on each code change
    npm test
    
    # Do a single test run
    npm run test-single-run

    #
    npm run update-webdriver

    #
    npm run protractor
