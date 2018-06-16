
# Website Performance Optimization portfolio project
Your challenge is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the Critical Rendering Path course.


## Getting Started
You can *[clone](https://github.com/CindyLouWho2/CindyLouWho2.github.io.git)* or *[download](https://github.com/CindyLouWho2/CindyLouWho2.github.io.git)* this project via [GitHub](https://github.com) to your local machine.

Part 1: Optimize PageSpeed Insights score for index.html 

![Using ngrok](./Desktop.png)
![Using ngrok](./Mobile.png)


## Modifications to index.html to achieve at least a 90 PageSpeed score.  
_____________________________________________________________________________________________________


1. CSS styles file was removed and inlined in HTML

2. Added a media query for print
3. Moved the JS to end of HTML document
4. Removed the Google Analytics
5. Optimized all images by using *[download](https://tinyjpg.com)* and/or *[download](https://online-convert.com)*
6. Replaced Google webfont

## Modifications to pizza.html and main.js to obtain a FPS of 60.
__________________________________________________________________________________________________

1. Optimized all images by using *[download](https://tinyjpg.com)* and/or *[download](https://online-convert.com)*
2. Replaced querySelectorAll with getElementsByClassName
3. Moved multiple variables out of the For loops so they would be ran everytime the loop was
4. Reduced number of moving pizza's from 200 to 30 based on screen size



