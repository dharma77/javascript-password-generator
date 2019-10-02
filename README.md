# JavaScript Password Generator

Hi, this project is based on the [Project Nayuki - Random password generator (JavaScript)](https://www.nayuki.io/page/random-password-generator-javascript) :clap:

What I've done with the original Nayuki password generator is: 
* add better graphic layout and made it responsive :iphone:
* separate out the logic and stylesheets from HTML :twisted_rightwards_arrows:
* added strong password checker :muscle: --> [`zxcvbn`] (https://github.com/dropbox/zxcvbn)
* more to come :fire:

## Usage

See the example [`index.html`](index.html)

## Character set

| Options      |   Default  | Description                                                                            |
|--------------|:----------:|----------------------------------------------------------------------------------------|
| `number`     |   `true`   | Include number [0-9]                                                                   |
| `lowercase`  |   `true`   | Include lower case alphabet [a-z]                                                      |
| `uppercase`  |   `true`   | Include uppercase alphabet [A-Z]                                                       |
| `symbol`     |   `true`   | Include these symbols (`` !"#$%&'()*+,-./:;<=>?@[\\]^_`{\|}~ ``)                       |
| `space`      |   `false`  | Include `<space>`                                                                      |
| `custom`     |   `false`  | If you want to add some other characters other than above, specify here. E.g. `'你好'` |

## Length or strong set

| Options      |   Default  | Description                                                                            |
|--------------|:----------:|----------------------------------------------------------------------------------------|
| `lengthType` | `'length'` | Accept 'length' _(number of characters)_ & 'entropy' _(in bit)_                        |
| `length`     |    `12`    | Depends on `lengthType`, either in length or bit. Accept integer only                  |


## Contact

Email: [info@enricobez.it](mailto:info@enricobez.it) 

Website: [enricobez.it](https://enricobez.it) 

