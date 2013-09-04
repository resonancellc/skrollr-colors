skrollr-colors
==============

parse ``data-`` tags and convert different colors annotations to HSLA to allow transitions in skrollr.

How to use:
--------------

Include the plugin before ``skrollr.js`` and enjoy.  

    <script src="js/skroll-colors.min.js"></script>
    <!-- skroll.js code -->
    </body>
    
Now you can use codes like:

    <div 
        data-0="background-color: #000;"
      data-400="background-color: hsl(100,80%,90%,1);"
      data-top="background-color: rgba(255,255,255,1);">
        WHOOT
    </div>
    

Example:
-------------
[JSFiddle](http://jsfiddle.net/zqcx4/)


Supported color annotations
--------------

- HEX 3 digits: #F0F
- HEX 6 digits: #F0F0F0
- RGB: rgb(0,0,0)
- RGBA: rgba(0,0,0,0)
- HSL: hsl(0,0%,0%)

ToDo
----------

- Add support for spaces between values
- Find a way to convert HEX to HSL in one step
