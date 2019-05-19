<p align="center">
 <img src="images/logo.png" height="200"><br/>
Powerfull Simple XSS Scanner made with python 3.7
</p>

## Installing

Requirements: <br/>

<li> BeautifulSoup4 </li>

```bash
pip install bs4
```
<li> requests </li>

```bash
pip install requests
```
<li> python 3.7 </li>
<br/>
Commands:

```bash
git clone https://github.com/menkrep1337/XSSCon
cd XSSCon
python3 xsscon.py --help 
```
## Usage
Basic usage:

```bash
python3 xsscon.py -u http://testphp.vulnweb.com
```
<br/>
Advanced usage see help:

```bash
python3 xsscon.py --help
```
## Screenshot

<img src="images/screenshot.png">

## Roadmap

v0.3B:
------
<li> Added custom options ( Such --proxy, --user-agent etc... )</li>
<li> First launched </li>
<br/>

v0.3B Patch:
------
<li>Added support for form method GET</li>
