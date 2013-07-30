vvv-logo
========

A small PaperJS experiment using the Vuvuvultures logo.

Usage:
------
1. Fire up the demo locally or at http://rawgithub.com/dylansmith/vvv-logo/master/vvv-logo.html
2. Play with the toggles

Geek out:
---------
The animation runs off a configuration, which is accessible in the JS console. Open your dev
console and inspect the window.vvv object to all the things you can play with. For example, try
the following commands:

vvv.config.triangles.strokeWidth = 20;
vvv.config.triangles.opacity = 1;
vvv.config.triangles.strokeColor = 'lime';
vvv.config.chaos.strokeMax = 50;

If you want to change the radius of the entire logo, you need to run update() to recalculate
some things, e.g.

vvv.config.radius = 300;
vvv.update();