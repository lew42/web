How to handle overlap?  We have web performance, JS performance, and lots of *-performances.. 

There are pretty hard lines when it comes to web stuff.  Is it JavaScript, or HTML?  There are certain things that do crossover, like loading scripts, for example.  Those things should be listed in both locations, and point to a third - a general web concepts.

For example, DOM stuff is about HTML and JavaScript.  JS related to DOM does not pertain to general JS stuff.  If you're interested in JS performance, are you interested in DOM performance?  What if you're working on a canvas library that doesn't touch the DOM.  You might want to exclude DOM performance optimizations from your queries.

We can't "query", we have to micro-manage our lists.
