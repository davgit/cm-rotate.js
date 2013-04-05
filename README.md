cm-rotate.js
============

Rotate js using CSS translate3d and transition

 * No dependencies
 * Works in all major browsers that support CSS translate3d or transition (IE9+)
 * Works on tablet PC
 * MIT License
 
[Example](http://work.cmiscm.com/cm-rotate.js/)  -  [Blog](http://blog.cmiscm.com/)



### Usage ###

Download the js file and include it in your html.
```html
    <script type="text/javascript" src="CMRotate.js"></script>
```

Add CMRotate.init function in your Javascript code.
```html
    var backgroundImages = ["images/img1.jpg", "images/img2.jpg", "images/img3.jpg", ...];

    CMRotate.init('rotate-div', 200, 300, 100, 12, 600, backgroundImages, clickFn);

    function clickFn(no) {
        alert('click no - ' + (no + 1));
    }
```



## License ###
Copyright (c) 2013 Jongmin Kim (http://cmiscm.com) 

Licensed under the MIT license.

 - http://www.opensource.org/licenses/mit-license.php

Older releases can be found on [google code][older]
[older]: http://code.google.com/p/jstree/downloads/list
