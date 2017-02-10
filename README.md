## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

####Part 1: Optimize PageSpeed Insights score for index.html

1. Download the project .

2. Open index.html.

##### Optimisations made:

1. Miniied print.css and added media="print".

2. Optimisied and compressed the images.

3. Moved js to bottom for faster loading and declared as async.

4. Inlined style.css

####Part 2: Optimize Frames per Second in pizza.html

######Our aim to optimize views/pizza.html, by modifying main.js until your frames per second rate is 60 fps or higher.

#####Optimisation used

1. Moved dx newwidth and out of for loop.

2. Changed querySelector to getElementByClassName.

3. changed querySelectorAll('.mover') to document.getElementBYClassName('mover')

4. Moved document.body.scrollTop to var phasetop