<p align="center">
 <img src="images/logo.png" height="200"><br/>
A powerful XSS scanner made in python 3.7</p>

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
chmod 755 -R XSSCon/
cd XSSCon
python3 xsscon.py --help 
```
## Usage
Basic usage:

```bash
python3 xsscon.py -u http://testphp.vulnweb.com
```
<br/>
Advanced usage:

```bash
python3 xsscon.py --help
```
## Screenshot

<img src="images/screenshot.png">

## Roadmap

v0.3B:
------
<li> Added custom options ( --proxy, --user-agent etc... )</li>
<br/>

v0.3B Patch:
------
<li>Added support for ( form method GET ) </li>

v0.4B:
------
<li>Now Multiple parameters for GET method is Supported</li>

## Note
* Sorry for my bad english 
* if you run xsscon on the win10 terminal you will get an untidy output
