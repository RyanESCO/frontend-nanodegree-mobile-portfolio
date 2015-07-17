Modifications for Optimization:

1)  compress and resize all images
2)  Remove web fonts 
3)  Make tracking js asynchronous
4)  Move render blocking scripts and css to end of html
5)  Replace all querySelectorAll with getElementByClassName
6)  Modify Change Pizza Slices by pulling out repeated calculations out of the foor loop so they are only calculated once
7)  calculate pizza 'phases' once instead of recalculating every time for every pizza
8)  Modify the number of pizzas to be dependent on screen size