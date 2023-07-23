![Version 1.13](https://img.shields.io/badge/Version-1.13-green.svg)
![Python 2.7.x](https://img.shields.io/badge/Python-2.7.x-yellow.svg)
[![GPLv3 License](https://img.shields.io/badge/License-GPLv3-red.svg)](https://github.com/D35m0nd142/LFISuite/blob/master/COPYING.GPL)
[![Twitter](https://img.shields.io/badge/Twitter-%40d35m0nd142-blue.svg)](https://www.twitter.com/d35m0nd142)

# LFI Suite

![alt tag](https://github.com/D35m0nd142/LFISuite/blob/master/screen.png)

<h3> What is LFI Suite? </h3>

This version of LFI Suite is able to scan Local File Inclusion vulnerabilities using many different methods. Note that this version has NO automatic exploit functionality, as this would prevent its use on the OSCP exam.

Automatic update functionality was also REMOVED to more easily facilitate its usage in tunneling and proxy scenarios.

* * * 

<h3> Features </h3>

* Works with Windows, Linux and OS X
* Automatic Configuration 

<h3> How to use it? </h3>

Usage is extremely simple and LFI Suite has an easy-to-use user interface; just run it and let it lead you.

python2 lfisuite.py

<h3> Dependencies </h3>

* Python <b>2.7</b>.x
* Python extra modules: termcolor, requests
* socks.py 

> When you run the script, in case you are missing some modules, it will check if you have <b>pip</b> installed and, in case you don't, it will install it <b>automatically</b>, then using pip it will install also the missing modules and download the necessary file <b>socks.py</b>.<br>I tried it on different operating systems (Debian,Ubuntu,Fedora,Windows 10,OS X) and it worked great, but if something strange happens to you and the automatic installation of pip and other modules fails, please install missing modules manually and re-run the script.
<br>![#f03c15](https://placehold.it/15/f03c15/000000?text=+) <b>IMPORTANT: In order to allow the script to install missing modules (and in case pip) automatically, you MUST run the script as root (or, at least, with sufficient permissions) the first time.</b>

