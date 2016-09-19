# Wireframe-Test
Wireframe-Test


SASS
====
I was unable to use SASS to generate the CSS as I do not have a SCSS processor installed on my machine.

CSS
===
There is no use of external libraries such as Bootstrap.

JAVASCRIPT
==========
There is no use of JavaScript.

BREAKPOINTS
===========
I have set a single breakpoint of 768px for mobile/tablet rendering. In desktop mode the page container width has a maximum
setting of 1300px above which the page is centered at 1300px width. Below 1300px width the container width is 100%.

TESTING
=======
Testing took place on Firefox 48, Chrome 53 & Explorer Edge.

SHOWING THE MENU IN MOBILE MODE
===============================
This was achieved in CSS with the use of the :target selector. Once the menu is opened it will remain opened until an item is 
clicked. Even a page refresh keeps the setting so seems to be native bwehaviour.

ARTICLE ASIDE LINKS
===================
I was unable to work out a method to float the aside links right and within the article paragraph in desktop mode. Flex-box may be able to achieve this but i  am unfamiliar with it's usage.
