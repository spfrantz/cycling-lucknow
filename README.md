# Cycling Lucknow

This simple website contains information and personal reflections about cycling in and around the northern Indian city of Lucknow. I created it as an exercise for the excellent online course [CS50W: Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript).

The site is hosted on <a href="https://spfrantz.github.io/cycling-lucknow/">GitHub Pages</a>.

## Pages

The site contains five pages:
* `index.html`: An introduction to the site;
* `routes.html`: A list of suggested cycling routes, including their distances, a link to a file that can be loaded into GPS units, and a link to an interactive map on the site Ride with GPS;
* `services.html`: A list of bicycle-related services available in Lucknow;
* `clubs.html`: Suggestions for how to join social or organized rides in the city;
* `reflections.html`: Some personal reflections on my year of cycling.

In addition, there is a folder for photos, another for GPX files, and a third for CSS files.

## Technical notes

The site is responsive, thanks mostly to Bootstrap. It is organized in two columns: a left column of text and a right column that contains a photo.

I have added additional responsiveness in `routes.html` to remove the embedded map and replace it with a link in viewports under 800 pixels.

The main stylesheet `styles.css` was generated from `styling.sass` using Dart.

## Areas for improvement

There are several areas where the page could be improved:
* It would be nice to have clickable photos, such that clicking them returns a pop-up window with a full-size photo;
* The embedded maps may be too large. I could consider making the `iframe` smaller. It's a matter of finding the right balance between usability and aesthetics. The embeds also slow the page down considerably, and at the moment they still load on smaller screens but are just hidden, which is inefficient;
* Some of the formatting is a bit contrived, so as to help me learn about CSS selectors.

## Comments

This was a useful exercise for me, and I hope the content will be of interest to at least a few. It forced me to read through the (surprisingly long!) [list of CSS selectors](https://www.w3schools.com/cssref/css_selectors.asp). It also helped me understand better how Bootstrap organizes webpages. I also  liked Sass and anticipate continuing to use it.
