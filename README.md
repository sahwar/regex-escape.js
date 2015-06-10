<!---------------------------------------------------------------------------->
<!-- STOP, LOOK & LISTEN!                                                   -->
<!-- ====================                                                   -->
<!-- Do NOT edit this file directly since it's generated from a template    -->
<!-- file, using https://github.com/IonicaBizau/node-blah                   -->
<!--                                                                        -->
<!-- If you found a typo in documentation, fix it in the source files       -->
<!-- (`lib/*.js`) and make a pull request.                                  -->
<!--                                                                        -->
<!-- If you have any other ideas, open an issue.                            -->
<!--                                                                        -->
<!-- Please consider reading the contribution steps (CONTRIBUTING.md).      -->
<!-- * * * Thanks! * * *                                                    -->
<!---------------------------------------------------------------------------->

# regex-escape [![Donate now][donate-now]][paypal-donations]

Escapes input characters to be used in regular expressions.

## Installation

```sh
$ npm i regex-escape
```

## Example

```js
// Dependencies
var RegexEscape = require("regex-escape");

console.log(RegexEscape("{#/}"));
// => \{#\/\}

```

## Documentation

### `RegexEscape(input)`
Encodes a string for using in a regular expression.

#### Params
- **String** `input`: The string that must be encoded.

#### Return
- **String** The encoded string.

### `proto()`
Adds the `RegexEscape` function to `RegExp` class.

#### Return
- **Function** The `RegexEscape` function.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Thanks
Big thanks to [CoolAj86](http://stackoverflow.com/users/151312/coolaj86) for
posting [this answer](http://stackoverflow.com/a/6969486/1420197). This library
uses the black magic regex from that answer. :sparkles:

## License
[KINDLY][license] © [Ionică Bizău][website]–The [LICENSE](/LICENSE) file contains
a copy of the license.

[license]: http://ionicabizau.github.io/kindly-license/?author=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica@gmail.com%3E&year=2015
[contributing]: /CONTRIBUTING.md
[website]: http://ionicabizau.net
[docs]: /DOCUMENTATION.md
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MG98D7NPFZ3MG
[donate-now]: http://i.imgur.com/jioicaN.png