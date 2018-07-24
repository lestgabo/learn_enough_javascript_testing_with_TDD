# Phrase object (with palindrome detector)

Sample NPM module created in Learn Enough JavaScript to Be Dangerous tutorial by Michael Hartl.

The module can be used as follows:
```
$ npm install --global beeftosino-palindrome
$ vim test.js
let Phrase = require("beeftosino-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```