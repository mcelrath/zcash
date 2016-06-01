Zcash Core 0.11.3.z4
=====================

Setup
---------------------
[Zcash Core](https://z.cash/) is the original Zcash client and it builds the backbone of the network. However, it downloads and stores the entire history of Zcash transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Zcash on your native platform.

### Unix

You need the Qt4 run-time libraries to run Zcash-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/zcash-qt (GUI, 32-bit) or bin/32/zcashd (headless, 32-bit)
- bin/64/zcash-qt (GUI, 64-bit) or bin/64/zcashd (headless, 64-bit)

[Zcash](https://z.cash/) is the Zcash client. It downloads and stores the entire history of Zcash transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

### Need Help?

* See the documentation at the [Zcash Wiki](https://github.com/zcash/zcash/wiki) for help and more information. NOTE: Other documentation in this directory may be out of date and inaccurate.
* Ask for help on the [Zcash](https://forum.z.cash/) forums.

Building
--------

Build Zcash along with most dependencies from source by running ./zcutil/build.sh. Currently only linux is supported.

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
