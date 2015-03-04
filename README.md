# All-the-time

This project takes the standard ui from the timesheet entry application for cvent employees and transforms it into something useable.

## Prerequisites

If you want to work on the project, you'll need the following:

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

Otherwise, the intent of this is simply to produce a chrome extension, which will be distributed through releases.

## Installation for development

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* add the chrome-dev/ directory as an extension to your chrome
* visit timesheet/ in your browser, refresh as necessary
* when adding new features, please start by adding a related test first.

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

* once app is built, dist should include an index file
* follow google instructions to package new dist: https://developer.chrome.com/extensions/packaging

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* [chrom-extensions documentation](https://developer.chrome.com/extensions)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
