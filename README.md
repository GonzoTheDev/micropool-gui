# micropool-gui
Minimal Crypto Pool

![screenshot](https://media.discordapp.net/attachments/809863850526244865/816388094613520424/micropool.png)



How to Guide: https://github.com/GonzoTheDev/crypto/wiki/Crypto-Micropool-How-to-Guide

To run micropool-gui as a nodejs/electronjs app:

    $ npm install electron -g
    $ git clone https://github.com/GonzoTheDev/micropool-gui.git
    $ cd micropool-gui
    $ npm install
    $ npm start

To build the micropool as a standalone executable:

    $ npm install electron-builder -g
    $ git clone https://github.com/GonzoTheDev/micropool-gui.git
    $ cd micropool-gui
    $ npm install
    $ electron-builder --linux
    $ electron-builder --windows
    $ electron-builder --mac
