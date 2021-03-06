## js-browser

## [!!!] The source code of this package is on [https://github.com/docomodigital/js-utils](https://github.com/docomodigital/js-utils), this repository will be removed asap

[![Build Status](https://travis-ci.com/docomodigital/js-browser.svg?branch=master)](https://travis-ci.com/docomodigital/js-browser)
[![Coverage Status](https://coveralls.io/repos/github/docomodigital/js-browser/badge.svg?branch=master)](https://coveralls.io/github/docomodigital/js-browser?branch=master)
[![npm version](https://badge.fury.io/js/%40docomodigital%2Fjs-browser.svg)](https://badge.fury.io/js/%40docomodigital%2Fjs-browser)
[![Greenkeeper badge](https://badges.greenkeeper.io/docomodigital/js-browser.svg)](https://greenkeeper.io/)

Provides you an alternative method to manage previous and current page changements.

Is particularly used to get query params as object and to get the previous page in order to implement an easy and basic history in your routing.

## Usage
```javascript
import { Browser } from 'js-browser';

// Get previous page
const prevPage = Browser.getPrevPage();

// Set browser new state
Browser.shiftPage('/home'); 

// Get query params in your url
const queryParams = Browser.getQueryParams();
```

## Installation

### NPM
```bash
npm install --save @docomodigital/js-browser
```

## Documentation

To read documentation, go to:

[http://docomodigital.github.io/js-browser/latest](http://docomodigital.github.io/js-browser/latest)

or run the following command insite the js-browser folder: 
```bash
npm run doc:open
```
