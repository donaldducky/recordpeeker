# Record Peeker

Peeks at FFRK battle drops data. Could potentially be expanded to do other things.

## Installation

Note: Only tested on OS X. Will probably work on Windows and Linux as long as mitmproxy works too.

Assuming you have [Homebrew](http://brew.sh) installed:

```
brew install python
pip install git+https://github.com/jonchang/recordpeeker.git
```

## Usage

In your Terminal, just type in:

```
recordpeeker
```

Then, set up your phone to use your computer as a proxy. Here's what it might look like on iOS:

![iOS manual proxy configuration](https://mitmproxy.org/doc/screenshots/ios-manual.png)

Enter a battle, and watch the drops roll in!

## Contributing

* Currently, the item database only includes equipment (i.e., no orbs or anything else). Edit [items.csv](https://github.com/jonchang/recordpeeker/blob/master/recordpeeker/data/items.csv) to add new things to the database.

* Functions wishlist
    * Suggest equipment optimizations
    * Record drop frequencies

## Developing

```
git clone https://github.com/jonchang/recordpeeker.git
cd recordpeeker
virtualenv env
source env/bin/activate
./setup.py develop
```

## License

This software is licensed under the [MIT License](http://choosealicense.com/licenses/mit/). For more information, see the `LICENSE` file.

## Inspiration

* [Snapception](https://github.com/thebradbain/snapception/)

