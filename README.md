## Website Performance Optimization portfolio project

This project is about putting the lessons from the Website Performance Optimization course to the test.  I have made several changes to the site, and hopefully it is enough to deliver a smooth experience.

### Getting Started

The page that fulfills the PageSpeed Insight score can be viewed [here](https://leboer.github.io/Project-Mobile-Portfolio/).

The result from the PageSpeed Insight can be viewed [here](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fleboer.github.io%2FProject-Mobile-Portfolio%2F&tab=mobile). (95/96 is what I'm getting)

The page that is optimized for frame rate can be viewed [here](https://leboer.github.io/Project-Mobile-Portfolio/views/pizza.html).

### Optimizations I have introduced

####Part 1: Optimize PageSpeed Insights score for index.html

1. Inlined the CSS
2. Asynced google analytics
3. Asynced google fonts by adding a script to the footer
4. Reduced the size of images

####Part 2: Optimize Frames per Second in pizza.html

1. Removed most of the FSL from resizing pizzas
2. Removed most of the FSL from scrolling
3. Reduced the size of the sliding pizza
4. Reduced the number of generated sliding pizzas
