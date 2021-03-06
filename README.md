# Vault-password-manager

Vault Password Manager is a web app for storing and retrieving secrets from [Vault](https://www.vaultproject.io). It is built using Ember.js

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)
* [Vault](https://www.vaultproject.io) (requires edge version to be compiled manually)
* [CORS-proxy](https://github.com/gr2m/CORS-Proxy) (or similar)

## Installation

* `git clone https://github.com/megahbite/vault-password-manager` this repository
* change into the new directory
* `npm install`
* `bower install`
* configure `config/enviornment.js`

## Running / Development

* `ember server`
* `vault server`
* `corsproxy`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
