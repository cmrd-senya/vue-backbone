# vue-backbone  

[![Build Status][travis-image]][travis-url]
[![Coverage Status][coveralls-image]][coveralls-url]
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

Vue.js Plugin to facilitate gradual migration from Backbone. Backbone Collections and Models can be safely integrated with Vue instances and components, with focus on clean code and future adoption of a Flux library (e.g. Vuex/Redux/Flux).

## Features

* Reactive data ensures Vue correctly and efficiently updates.
* Safe direct data access (`model.prop` vs `model.get('prop')`).
* Backbone-encapsulated logic made available.
* No syncing required, single source of truth.
* Step-by-step incremental migration path.

## Documentation

Usage and guidelines documentation available [here](https://mikeapr4.gitbooks.io/vue-backbone/guidelines.html) 

## Installation

Via NPM

    npm install vue-backbone

Via Yarn

    yarn add vue-backbone

## Examples

Clone or download the repo to run the examples.

* [*GitHub Commits*](https://github.com/mikeapr4/vue-backbone/tree/master/examples/github-commits.htm) - Backbone version of Vue.js example
* [*TodoMVC*](https://github.com/mikeapr4/vue-backbone/tree/master/examples/todomvc) - combined Backbone and Vue TodoMVC examples
* [*TodoMVC with Component*](https://github.com/mikeapr4/vue-backbone/tree/master/examples/todomvc-with-component) - more complex version of above
* [*Comparison*](https://github.com/mikeapr4/vue-backbone/tree/master/examples/comparison) - in-browser performance test and comparison

## License

[MIT](http://opensource.org/licenses/MIT)