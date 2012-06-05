urlize
======

An urlize module for Node. Turns URLs into prettier (?), easier to handle URLs.

1. Turns everything into lowercase
- Removes accents: äöå -> aoa
- Removes other characters than (i.e. keeps the following characters): `a-z 0-9 . _  -  (  ) /`
- Trims the string

##Usage

npm install git://github.com/ile/urlize.git

> var urlize = require('urlize').urlize; 


> urlize("  ääliö älä lyö, ööliä läikkyy.HTML");  
> // aalio-ala-lyo-oolia-laikkyy.html

##Disclaimer

Doesn't handle many foreign characters. 