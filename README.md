# hackbeanpot
This is a progressive exercise which starts with writing basic, semantic html and ends with advanced javascript that manipulates the browser history object. Along the way you'll be adding CSS, making that CSS responsive for a smaller viewport, adding a google font, and then referencing the jQuery library to turn your webpage into a single-page application.

step1.html (basic html structure):
1. create new text doc, save as "webworkshop.html" (or any filename with an .html extension - index.html, etc)
2. open in text editor
3. create a basic semantic html5 structure
	-grab some images and create some text!
Note: "semantic html" is important for search engine readability, as well as providing solid coding structure for developer readability.

step2.html (styles):
1. styles
2. font awesome (https://www.bootstrapcdn.com/fontawesome/)
Note: well-structured CSS is a beautiful and powerful thing. It smooths out cross-browser quirks and provides one area from which you can control much of your site's layout and design. Because CSS "cascades", later style declarations will override previous declarations (with the exception of the !important callout). Fontawesome provides a library of vector graphics (SVGs) that will scale without loss.

step3.html (responsive design):
1. media query for responsive views
2. viewport tag
3. google font (fonts.google.com)
Note: media queries are able to identify the way a user is viewing a site so a developer can accomodate these different use cases. It is not just limited to screen size, but print vs screen, landscape vs portrait, and other cases.

step4.html (add javascript):
1. go to code.jquery.com, grab minified link
2. "console" and "debugger"
3. responsive menu toggle
Note: jQuery is a powerful Javascript library that enables easy manipulation of elements using the DOM (Document Object Model), with excellent support for ajax.

final.html (more javascript):
1. browser history
2. enclose in IIFE
Note: up to this point, the single-page application does the job, but does not contribute much to shareability. Modifying the browser history allows the experience to be shared between users.

Finally...
This single-page site was built with graceful degradation in mind. Many page crawlers use Javascript, but there is the off-chance that they won't, or a library fails to load, or simply takes too long while your user is loading the site on their mobile device while going through an area with poor service. Designing sites that will show relevant content without requiring that Javascript be loaded does require extra effort, but ensures you cover all the bases. At the end of the day, people come to the "information superhighway" for information, and that information should be as accessible and relevant as possible.

References:

-https://developer.mozilla.org

-http://code.jquery.com

-https://www.bootstrapcdn.com/fontawesome/
