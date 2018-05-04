# Feed Reader Testing Nanodegree Project

In this project we have a web-based application that reads RSS feeds. We have [Jasmine](http://jasmine.github.io/) and we started writing tests suite!



# Run this application 

You have to open index.html in your browser to run this application.

The tests are in the feedreader.js file and the test results appears at the bottom of the index.html page. Green tests have passed and red ones have failed.



## The tests


- Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
- Return the `allFeeds` variable to a passing state.
- loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
- loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
- Write a new test suite named `"The menu"`.
- ensures the menu element is hidden by default. (analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.)
- Write test to ensure the menu changes visibility when the menu icon is clicked.(does the menu display when clicked and does it hide when clicked again.)
- Write a test suite named `"Initial Entries"`.
- test to ensure when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
- Write a test suite named `"New Feed Selection"`.
- Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
- No test should be dependent on the results of another.
- Callbacks should be used to ensure that feeds are loaded before they are tested.
- Implement error handling for undefined variables and out-of-bound array access.
- When complete - all the tests should pass. 