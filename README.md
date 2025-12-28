# <img src="https://user-images.githubusercontent.com/4319621/36906314-e3f99680-1e35-11e8-90fd-f959c9641f36.png" alt="Notepadqq" width="32" height="32" /> Notepadqq [![CI](https://github.com/notepadqq-team/notepadqq-ng/actions/workflows/ci.yml/badge.svg)](https://github.com/notepadqq-team/notepadqq-ng/actions/workflows/ci.yml)

### Links

* [What is it?](#what-is-it)
* [Build it yourself](#build-it-yourself)
* [Download it](#distribution-packages)

#### What is it?

Notepadqq-ng is fork of Notepadqq, a text editor designed by developers, for developers. 

![screenshot_20180302_163505](https://notepadqq.com/s/images/snapshot1.png)

Please visit our [Wiki](https://github.com/notepadqq-team/notepadqq-ng/wiki) for more screenshots and details.

Build it yourself
-----

| Build dependencies    | Dependencies      |
|-----------------------|-------------------|
| Qt 5.6 or higher      | Qt 5.6 or higher  |
| qtwebengine5-dev      | qtwebengine5      |
| libqt5websockets5-dev | libqt5websockets5 |
| libqt5svg5-dev        | libqt5svg5        |
| qttools5-dev-tools    | coreutils         |
| libuchardet-dev       | libuchardet       |
| pkg-config            |                   |

#### Get the source

    $ git clone --recursive https://github.com/notepadqq-team/notepadqq-ng.git
    $ cd notepadqq

#### Build

    notepadqq$ ./configure --prefix /usr
    notepadqq$ make

If you encounter errors make sure to have the necessary libraries installed. For Ubuntu you can do that using apt-get:

    sudo apt-get install qttools5-dev-tools qtwebengine5-dev libqt5websockets5-dev libqt5svg5 libqt5svg5-dev libuchardet-dev pkg-config

For CentOS:

    sudo yum install -y qt5-qtbase-devel qt5-qttools-devel qt5-qtwebengine-devel qt5-qtwebsockets-devel qt5-qtsvg-devel uchardet qt5-qtwebchannel-devel pkgconfig

#### Install

You can run notepadqq from its build output folder. If however you want to install it, first build it
by following the above steps, then run:

