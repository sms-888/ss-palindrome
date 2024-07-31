# Pharase object (with Palindrome detector)

This is a sample npm module created in [*Learn Enough JavaScript to Be Dangerous*](https://www.learnenough.com/javascript-tutorial).

The module can be used as follows:

    $ npm install --global ss-palindrome
    $ vim test.js
    let Phrase = require("ss-palindrome");
    let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
    console.log(napoleonsLament.palindrome());
    $ node test.js
    true