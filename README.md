# [Feed Reader Testing Project](https://alfred-kctang.github.io/feed-reader-testing/)

## Table of Contents

* [Project Background](#projectBackground)
* [The Tests](#theTests)
* [How to Run the Application](#howToRuntheApplication)
* [Contributing](#contributing)
* [License](#license)

## Project Background

In this project, a web-based application that reads RSS feeds was provided. My task is to write a number of tests against this pre-existing application by using Jasmine, a JavaScript testing framework. These tests will test the underlying business logic of the application as well as the event handling and DOM manipulation.

## The Tests

The project contains four test suites as follows:

1. The first test suite tests against RSS feeds definitions: to test whether (i) the allFeeds variable, (ii) the URL of each feed and (iii) the names of each feed have been defined and are not empty.
2. The second one tests against the menu: to test (i) whether the menu element is hidden by default as well as (ii) the menu's hiding/showing functionality - whether the menu displays when the menu icon is clicked and whether it hides when the icon is clicked again.
3. The third one tests against the initial entries: to test whether there is any entry elements inside the feed container in the DOM, when the loadFeed function is called.
4. The fourth one tests against the new feed selection: to test whether the entries content changes when a new feed is loaded by the loadFeed function.

## How to Run the Application

1. Under the repository name, click **Clone or download**.
2. In the Clone with HTTPs section, copy the clone URL for the repository
3. Open Terminal.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type `git clone`, and paste the URL you copied, and then press enter.
6. Open the `index.html` and check the test results.
7. You might modify the functionality in `app.js` to test against whether the tests work!

**OR**

1. Click on this [link](https://alfred-kctang.github.io/Feed-Reader-Testing-Project/) to open the live version of the page.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

This repository is covered under the [MIT License](https://choosealicense.com/licenses/mit/).
