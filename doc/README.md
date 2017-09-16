Snekcoin Core 1.10
==================

Setup
---------------------
[Snekcoin Core](http://snekcoin.com/) is the reference Snekcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Snekcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Snekcoin on your native platform.

### Unix

You need the Qt4 run-time libraries to run Snekcoin-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/snekcoin-qt (GUI, 32-bit) or bin/32/snekcoind (headless, 32-bit)
- bin/64/snekcoin-qt (GUI, 64-bit) or bin/64/snekcoind (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run snekcoin-qt.exe.

### OSX

Drag Snekcoin-Qt to your applications folder, and then run Snekcoin-Qt.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#snekcoin](http://webchat.freenode.net?channels=snekcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=snekcoin).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Snekcoin thread](https://bitcointalk.org/index.php?topic=361813.0).

Building
---------------------
The following are developer notes on how to build Snekcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Snekcoin repo's [root README](https://github.com/snekcoin/snekcoin/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Snekcoin thread](https://bitcointalk.org/index.php?topic=361813.0).
* Discuss on [#snekcoin-dev](http://webchat.freenode.net/?channels=snekcoin-dev) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=snekcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the Bitcoin developers for use in [Bitcoin Core](https://www.bitcoin.org/). 
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
