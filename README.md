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
5. Optimized all images by using *[tinyjpg](https://tinyjpg.com)* and/or *[download](https://online-convert.com)*
6. Replaced Google webfont

## Modifications to pizza.html and main.js to obtain a FPS of 60.
__________________________________________________________________________________________________

1. Optimized all images by using *[download](https://tinyjpg.com)* and/or *[download](https://online-convert.com)*
2. Replaced querySelectorAll with getElementsByClassName
3. Moved multiple variables out of the For loops so they would be ran everytime the loop was
4. Reduced number of moving pizza's from 200 to 30 based on screen size



## Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
