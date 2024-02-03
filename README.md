[![en](https://img.shields.io/badge/lang-en-gray.svg)](/README.md)
[![ru](https://img.shields.io/badge/lang-ru-blue.svg)](/README.ru.md)

## TorrServer for Windows 7
Original project repository: [TorrServer](https://github.com/YouROK/TorrServer)

This repository only autobuilds [TorrServer](https://github.com/YouROK/TorrServer) releases using legacy go1.21.4 for Windows.

This assembly is fully automated and provided by AS-IS.<br>
You can find the build script in the repository.<br>
Build starts 15:30 UTC daily (18:30 MSK).

<hr> 

Starting with go1.21.5, applications built using it do not run on Windows 7.<br>
TorrServer Matrix.129 is already built using go1.21.6 and it does not run on Windows 7.

Support for Windows 7 ended with go1.21.0, but applications still worked up to version 1.21.4 inclusive.<br>
TorrServer uses components only available in go1.21.

Thus, it is unknown how long it will be possible to support the build using go1.21.4, the latest compatible with Windows 7.