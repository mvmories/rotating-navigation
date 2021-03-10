# rotating-navigation

3/50: 
This is the third of fifty projects, that i will be doing in the next 50 days.
The idea is to use html, css and vanilla javascript to improve my skills.

In this project I created a simple web page that contains a fixed circle menu, and a hidden footer menu.

When we click the menu-open button (within the fixed circle container menu), it triggers an event animation that rotates both the content of the page and the menu circle itself, revealing:
(i) the option to close the menu; and
(ii) the hidden footer menu - which also eases in with a simple delayed animation.

Most of the work was done using html and css. The javascript on this project is very simple: we basically access the DOM to get the page container that has the page content, and add or remove a 'show-nav' classList style based on the button of the menu clicked (i.e. 'open' or 'close').