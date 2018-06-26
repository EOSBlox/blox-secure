# \<blox-secure\>

[![Build Status](https://travis-ci.org/EOSBlox/blox-secure.svg?branch=master)](https://travis-ci.org/EOSBlox/blox-secure)

AES encryption

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) and npm (packaged with [Node.js](https://nodejs.org)) installed. Run `npm install` to install your element's dependencies, then run `polymer serve` to serve your element locally.

## Install blox-secure

```
$ npm install blox-secure
```

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

## Import

```
$ import 'blox-secure';
```

## Basic Use

```html
<blox-secure
    password="secret!!"
    data="{{data}}"
    result="{{result}}">
</blox-secure>
```

## Javascript Use

```html
<blox-secure id="bloxSecure"></blox-secure>
<script>
    this.$.bloxSecure.secure('secret!!', data)
    .then((res) => {
        // Do Something
    })
    .catch((err) => {
        // Do Something
    })
</script>
```
