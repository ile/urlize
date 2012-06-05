urlize
======

An urlize module for Node. 

- Removes accents: äöå -> aoa
- Removes other characters than: a-z  0-9  _  -  (  ) 
- Turns everything into lowercase

##Usage

npm install git://github.com/ile/urlize.git


var urlize = require('urlize').urlize;
urlize("  ääliö älä lyö, ööliä , (läikkyy)  " ); // aalio-ala-lyo-oolia-(laikkyy)

