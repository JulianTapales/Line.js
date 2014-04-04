Line.js
=======

A JQuery based plugin in its baby steps for easy to implement, line based, CSS effects.

See demo here: http://tapjay.github.io/


To use
------

Link line.js and line.css to your webpage along with JQuery. Bind the classname to the appropriate function (see demo) and pass the parameters you want for duration, width, type of animation etc to the function as appropriate. 

That's it. Line.js takes care of wrapping the existing content in the class you bound to the function within a relative div (to preserve positioning), adds the elements to be animated and adds the appropriate CSS (for hardware accelarated animations) to the elements with your specified parameters. It also adds padding according to the thickness of line specified so the animations do not overlay the content.
