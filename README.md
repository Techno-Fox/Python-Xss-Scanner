# XssPy - Web Application XSS Scanner
A tool by Mktech

Author: MK 


# Great News: Xsspy was recently used by an engineer at microsoft to find a bug in Pentagon's Bug Bounty Program.
http://holisticinfosec.blogspot.com/2016/06/toolsmith-tidbit-xsspy.html



# Installation: 
Type the following in the terminal.

https://github.com/secureroot/Python-Xss-Scanner.git 

The tool works on Python 2.7 and you should have mechanize installed. If mechanize is not installed, type "pip install mechanize" in the terminal.

# Usage: 
`python XssPy.py website.com` (Do not write www.website.com OR http://www.website.com)

# Payloads
If you have found a XSS vulnerability, you can try the following payloads.
http://pastebin.com/J1hCfL9J

# Description: 
XssPy is a python tool for finding Cross Site Scripting vulnerabilities in websites. This tool is the first of its kind. Instead of just checking one page as most of the tools do, this tool traverses the website and find all the links and subdomains first. After that, it starts scanning each and every input on each and every page that it found while its traversal. It uses small yet effective payloads to search for XSS vulnerabilities. 

The tool has been tested parallel with paid Vulnerability Scanners and most of the scanners failed to detect the vulnerabilities that the tool was able to find. Moreover, most paid tools scan only one site whereas XSSPY first finds a lot of subdomains and then scan all the links altogether. The tool comes with:

1) Short Scanning
2) Comprehensive Scanning
3) Finding subdomains
4) Checking every input on every page

With this tool, Cross Site Scripting vulnerabilities have been found in the websites of MIT, Stanford, Duke University, Informatica, Formassembly, ActiveCompaign, Volcanicpixels, Oxford, Motorola, Berkeley and many more.


# NOTE: 
Mail me if you encounter any errors (1whenben@gmail.com). You can also post your problems on the website. I'll try my best to respond as soon as possible.


