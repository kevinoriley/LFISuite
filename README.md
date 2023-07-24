![Version 1.13](https://img.shields.io/badge/Version-1.13-green.svg)
![Python 2.7.x](https://img.shields.io/badge/Python-2.7.x-yellow.svg)
[![GPLv3 License](https://img.shields.io/badge/License-GPLv3-red.svg)](https://github.com/D35m0nd142/LFISuite/blob/master/COPYING.GPL)
[![Twitter](https://img.shields.io/badge/Twitter-%40d35m0nd142-blue.svg)](https://www.twitter.com/d35m0nd142)

# LFI Suite - OSCP Edition

<h3> What is LFI Suite? </h3>

This version of LFI Suite is able to scan Local File Inclusion vulnerabilities using many different methods. Note that this version has NO automatic exploit functionality, as this would prevent its use on the OSCP exam.

Automatic update functionality was also REMOVED to more easily facilitate its usage in tunneling and proxy scenarios.

Could not get termcolor working, so it was (sadly) also removed. Output isn't pretty, but it is functional.

All credit to the original author, d35m0nd142. Sorry to take a machete to your great tool just to satisfy OSCP exam requirements ;-) 

* * * 

<h3> Features </h3>

* Works with Windows, Linux and OS X
* Automatic Configuration 

<h3> How to use it? </h3>

Usage is extremely simple and LFI Suite has an easy-to-use user interface; just run it and let it lead you.

python2 lfisuite.py

<h3> Dependencies </h3>

* Python <b>2.7</b>.x
* Python extra modules: requests
* socks.py 
