# Romanian Bible
Romanian Bible module

## Installation
Run the following commands to download and install the application:

```sh
$ git clone git@github.com:BibleJS/bible-romanian.git bible-romanian
$ cd bible-romanian
$ npm install
```

## Example
```js
// Dependencies
var RoBible = require("../index");

// Get verse
RoBible.getVerse("Matei 1:1", function (err, data) {
    console.log(err || data);
});

// Get books
RoBible.getBooks(function (err, data) {
    console.log(err || data);
});
```

## How to contribute

1. File an issue in the repository, using the bug tracker, describing the
   contribution you'd like to make. This will help us to get you started on the
   right foot.
2. Fork the project in your account and create a new branch:
   `your-great-feature`.
3. Commit your changes in that branch.
4. Open a pull request, and reference the initial issue in the pull request
   message.

## License
See the [LICENSE](./LICENSE) file.
