# Library-app

The app is a `ember.js` basic curd web app which is backend server used `Django` restful `API`.

## Installation

* `git clone https://github.com/mbrsagor/ember-crud.git`
* `cd library-app`
* `yarn install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `yarn lint:hbs`
* `yarn lint:js`
* `yarn lint:js --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

## Installation 3rd party depandancy
- Install Bootstrap 
  - ```ember install ember-bootstrap```
- Install SCSS
  - ```ember generate ember-bootstrap --preprocessor=sass```
- Remove/Delete default `css`
  - ```emberrm ./app/styles/app.css```
