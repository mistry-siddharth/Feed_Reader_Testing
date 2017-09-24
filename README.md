# Feed_Reader_Testing
The objective of this project is to develop a test suite for a web-based application that reads RSS feeds. Jasmine was used to write a number of tests against a pre-existing application. These test the underlying business logic of the application as well as the event handling and DOM manipulation. To see the test cases, please refer to "Feed_Reader_Testing/jasmine/spec/feedreader.js".

# Installation
### Dependencies
- Jasmine (https://jasmine.github.io/)

### To run the application follow the following steps:
1. Download the GitHub zip file or clone the repository onto your local machine.
2. Open a browser window and navigate to the index.html file in your application's directory.

# Concepts
- Writing effective tests to analyze multiple aspects of an application including the HTML, CSS and JavaScript.
- Analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.

# Tests Performed
### RSS Feeds:
- All feed variables are defined.
- All feed URLs are defined and are not empty.
- All feed names are defined and are not empty.

### Menu:
- Menu is hidden by default on page load.
- Menu changes visibility (clicking once shows the menu content, and clicking it again hides the content) on click.

### Initial Entry:
- There should be at least one feed displayed on loading the page.

### New Feed Selection:
- Content of the feed changes when a new feed is loaded.
