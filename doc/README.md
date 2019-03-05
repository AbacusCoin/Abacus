ABA Core
=====================

Setup
---------------------

[ABa Wallet](https://github.com/CryptoCashBack-Hub/ABA/releases) is the original Aba client and it builds the backbone of the network. 
However, it downloads and stores the entire history of Aba transactions.
Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a couple of minutes to a few hours.


Running
---------------------
The following are some helpful notes on how to run ABA on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/aba-qt (GUI, 32-bit) or bin/32/abad (headless, 32-bit)
- bin/64/aba-qt (GUI, 64-bit) or bin/64/abad (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run aba-qt.exe.

### OSX

Drag ABA-Qt to your applications folder, and then run ABA-Qt.

### Need Help?


for help and more information.
* Join our forum on [BitcoinTalk](https://bitcointalk.org/index.php?topic=5089897.0).
* Join our Discord groups [Aba Discord Groups](https://discord.gg/mM8mS9V).


Building
---------------------
The following are developer notes on how to build ABA on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------

The Aba repo's [README](https://github.com/CryptoCashBack-Hub/ABA/blob/master/doc/README.md) contains relevant information on the development process and automated testing.


- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (Bitcoin)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources


* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=5089897.0).
* Join the Discord groups [Aba Discord Groups](https://discord.gg/mM8mS9V).


### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
