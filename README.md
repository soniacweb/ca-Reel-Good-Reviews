# Reel Movie Reviews 

Part of the codecademy frontend engineering path.

## Overview: 

Reel Movie Reviews is a popular movie review site that has hired your design company to help improve some of its mobile pages. They have noticed that they are not having users stay on the pages for individual movie reviews very long, and are often not clicking on any of the links to see more content that is present on the pages.

The movie review page for Get Out is shown to the right. Look through the page and determine how we can improve readability and navigation on this page by improving the text design.

# Tasks
0/11 Complete
Mark the tasks as complete by checking them off
1.
There’s no real way to distinguish what text is important on this page. Let’s start improving this page by adding header elements.

Turn “Recently Added Reviews” at the top of the page into an <h1> element.

2.
Make the movie titles, “Get Out” and “Daddy’s Home 2” into <h2> headers to make them easy to see.

3.
Make the names of the reviewers into <h3> elements.

4.
Let’s make all the headers stand out a bit more on the page. Add some contrast and change their color to something lighter.

In styles.css locate the styling for all the header selectors and add in a font color.


5.
It’s easy for a user to skim over the cast of the movie. Let’s try to make them stand out a bit more.

Turn the cast of the movie into list elements. Also, make sure the “see all” link after their names part of the list.


6.
Let’s make the styling of the list elements a little different so they stand out a bit. A good way to do this is by slightly changing the font size and adding some line-height.


7.
Let’s also make the title of the list stand out a bit more, create a class .stars-label and add some styling to make the title of the list visible.

Then add .stars-label to the first list element that has the text “Stars:”.


8.
We have two pieces of text that have the class “section-header”. One is on a black background and one is on a white background.

We want to create some more contrast for the one on the black background.

Create a new class “.featured-section-header” that changes the color of the text to white and add it to the “Now Trending”.


9.
Let’s make the section headers stand out a bit more. Bring their font up to 18px and make them all uppercase.


10.
The genres are really hard to read, look for the class .movie-description-category and fix the issue.


11.
Finally, notice there are two links “See All” and “See Reviews” that don’t easily stand out as buttons. Let’s make sure they are easily noticable by adding some background colors to them.

However, “See All” is on a dark background already and “See Reviews” in on a light background. Create a different class for each button and add a good contrasting background colors the links stand out.