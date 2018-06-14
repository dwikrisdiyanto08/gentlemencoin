Gents Core

Setup
Gents Core is the original Gents client and it builds the backbone of the network. However, it downloads and stores the entire history of Gents transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
The following are some helpful notes on how to run Gents on your native platform.

Unix
Unpack the files into a directory and run:

bin/32/gents-qt (GUI, 32-bit) or bin/32/gentsd (headless, 32-bit)
bin/64/gents-qt (GUI, 64-bit) or bin/64/gentsd (headless, 64-bit)

Windows
Unpack the files into a directory, and then run gents-qt.exe.

OSX
Drag Gents-Qt to your applications folder, and then run Gents-Qt.

Need Help?
Ask for help on BitcoinTalk or on the Gents Forum on discord.

Building
The following are developer notes on how to build Gents on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

OSX Build Notes
Unix Build Notes
Gitian Building Guide
Development
The Gents repo's root README contains relevant information on the development process and automated testing.

Developer Notes
Multiwallet Qt Development
Release Notes
Release Process
Source Code Documentation (External Link) TODO
Translation Process
Unit Tests
Unauthenticated REST Interface
Dnsseed Policy
Resources
Discuss on the BitcoinTalk or the Gents forum.
Join the Gents-Dev Slack group (Sign-Up).
Miscellaneous
Assets Attribution
Files
Tor Support
Init Scripts (systemd/upstart/openrc)

License
Distributed under the MIT/X11 software license. This product includes software developed by the OpenSSL Project for use in the OpenSSL Toolkit. This product includes cryptographic software written by Eric Young (eay@cryptsoft.com), and UPnP software written by Thomas Bernard.
