Welcome to speedy.js, a minimalist script (less than 4 KB) that renders page timings at the top of the page.  

Here is a basic example :

![demo](https://raw.githubusercontent.com/Cybermaxs/speedy.js/master/examples/chrome-example.png)

[Performance is a feature] (http://blog.codinghorror.com/performance-is-a-feature/) and everybody in your company should be educated and involved in this topic.
This script will allow everybody to have a quick overview of the timings.
It's definitely a good idea idea to use it during dev/staging environements.

#Basic usage
In the current version, speedy.js is not intrusive : You just have to include it _somewhere_ in you page. 
speedy.js will wait for the load event or run immediatly if the document is already fully loaded.

`<script src="PATHTOSPEEDY/speedy.min.js"></script>`

#Can I use ?
Navigation timing is not currently supported by all browser.
You can check requirements [here] (http://caniuse.com/#feat=nav-timing)

Here are the main results  : 
+ Internet Explorer 9
+ Firefox 7
+ Chrome 6
+ Safari 8
+ Opera 15
+ iOS Safari 8
+ Android browser 4
+ Opera Mobile 22
+ Blackberry 10

#More info
+ [HTML5 Navigation Timing API] (http://www.w3.org/TR/navigation-timing/)
+ [HTML5 Resource Timing API] (http://www.w3.org/TR/resource-timing/)


# Acknowledgements
+ @kaaes : author of http://kaaes.github.io/timing/
