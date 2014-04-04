Line.js
=======

A JQuery based plugin in its baby steps for easy to implement, line based, CSS effects. 

Attempts to make this type of effect easier to implement by reducing the amount of HTML required as code required for this effect is appended to the DOM on load.

See demo here: http://tapjay.github.io/


To use
------

Link line.js and line.css to your webpage along with JQuery. Bind the classname to the appropriate function (see demo) and pass the parameters you want for duration, width, type of animation etc to the function as appropriate. 

That's it. Line.js takes care of wrapping the existing content in the class you bound to the function within a relative div (to preserve positioning), adds the elements to be animated and adds the appropriate CSS (for hardware accelarated animations) to the elements with your specified parameters. It also adds padding according to the thickness of line specified so the animations do not overlay the content.


Note:
---------

This plugin is mobile responsive, but the demo is not. I'm aiming to make a better demo with bootstrap in future to show this.

In future:
----------

I aim to develop the effects more, they are a bit "messy" in their current state. This will likely consist of reversing the delays when the animation reverses to give the illusion of the line recceding back to its initial starting point. I also aim to add an easy way of triggering the effect when the element scrolls into view, most likely through the use of another plugin. I aim to also add a few additional effects, namely where the lines start at the centre of the top of the element and simultaneously trace the rectangular shape, meeting at the centre of the bottom of the element. Bear with me however, this is my first proper attempt making anything usefull with Javascript/JQuery and am still learning so the code may be badly written and/or messy. 
