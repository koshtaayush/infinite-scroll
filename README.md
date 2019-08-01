# infinite-scroll

Here’s a working implementation for reference.

A few notes:

1. we’re using robust methods to identify when to load the next batch: getScrollTop() and getDocumentHeight()
a loader is shown until the data is actually loaded
2. the page size was selected to reflect the average tab size for the content we used
the provided example isn’t optimized for performance at scale, to match a realistic time frame for an interview
3. See this article for some pointers on performance optimizations when implementing infinite scroll.
https://developers.google.com/web/updates/2016/07/infinite-scroller
