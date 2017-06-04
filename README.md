# Discogs Collection Basics

[![CircleCI](https://img.shields.io/circleci/project/github/sbstjn/discogs-basics.svg)](https://circleci.com/gh/sbstjn/discogs-basics)
[![license](https://img.shields.io/github/license/sbstjn/discogs-basics.svg)](https://github.com/sbstjn/discogs-basics/blob/master/LICENSE.md)
[![Coveralls](https://img.shields.io/coveralls/sbstjn/discogs-basics.svg)](https://coveralls.io/github/sbstjn/discogs-basics)

Minimal wrapper for the [Discogs](https://discogs.com) Collection API.

## Install

```bash
$ > yarn install discogs-basics
```

## Usage

First [create an access token](https://www.discogs.com/de/settings/developers) for accessing the Discogs API.

```javascript
const Discogs = new API('username', 'token')

# Get details about most recent record
Discogs.Last().then(console.log)

# Get number of items in your collection
Discogs.Items().then(console.log)

# Get maximum, minimum, median collection value
Discogs.Value().then(console.log)
```

## License

Feel free to use the code, it's released using the [MIT license](https://github.com/sbstjn/discogs-basics/blob/master/LICENSE.md).

## Contributors

- [Sebastian Müller](https://github.com/sbstjn)

## Contribution

You are more than welcome to contribute to this project! 😘

To make sure you have a pleasant experience, please read our [code of conduct](CODE_OF_CONDUCT.md). It outlines core values and believes and will make working together a happier experience.
