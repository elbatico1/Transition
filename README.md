Transition
========
javascript library for managing and create easy and cross browser animation.
Transition it's an ease and friendly way of taking advantages of requestAnimationFrame and build-in -transform feature of the magior browser.

Browser Support
--------

Transition has been tested and should work in
- Internet Explorer 7+
- Safari
- Firefox
- Chrome
- Opera

Examples
--------

I just begin to set it free so, for right now, there isn't much to show.
Some example and a draft documentation can be found at [www.somethinglikethis.it/transition](http://www.somethinglikethis.it/transition/).

Usage
--------

Transition has just one object:

* Transition

and a separated object **Colors** in wich are placed some utils for converting and manage colors.

### Transition
```
var tween=new Transition();
tween.addTweener(myobj,{param...,duration:mls,ease:"easeNone",onStart:function,onTween:function,onEnd:function,args:[obj]});
```
				
License
-------
Transition is released under [MIT license](http://opensource.org/licenses/mit-license.php).

Credits
-------
Transition javascript library was created by [Fabio Fantini](https://github.com/elbatico1/Transition). You can contact me at [info@somethinglikethis.it](mailto:info@somethinglikethis.it)
website : [somethinglikethis.it](http://www.somethinglikethis.it).