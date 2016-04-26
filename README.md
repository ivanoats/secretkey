# Secret Key Generator

Generates a secret key

## Installation

`npm -g install secretkey`


## Usage

`secretkey` - output secretkey to STDOUT

output is something like:
de6c32bf4f67b6531fdd89e37b2d2a9df0fa18090aabd8ff7495ac9abda967cf44a91a432fadf72f64ee59bf53f90ef4

*Don't use the one above unless you're in the running for a [Darwin Award](http://en.wikipedia.org/wiki/Darwin_Awards)*

e.g. on Mac OS X: `secretkey | pbcopy` will put a secret key on your clipboard.

## Credits

Credit is due to @thejh and @dimadima for their answers on http://stackoverflow.com/questions/8855687/secure-random-token-in-node-js

As well as Šime Vidas and Deviljho for their answer on http://stackoverflow.com/questions/5963182/how-to-remove-spaces-from-a-string-using-javascript
