# School Year In Review

[View the live demo](http://la-school-review.netlify.com/)

--------------------------------------------------------------------------------

All of the first name instances are labeled as:

```html
<!-- Learning Ally Member Frist Name -->
<span id=“first-name”>Carlos</span>

...
```

For the numbers in the statistics bar I am using CountUp.Js for the effect. The Count Up Variables are defined in the inline footer script at the bottom of the page.

**Importante Note: All of the reading stats are controlled by the CountUp.JS Script. I placed all of the custom init scripts in the html page for your reference.**

The number inside of the html element is overridden by countup, but I would input it there as well incase countup fails.

```javascript
// CountUp.JS Configuration
  var booksToShelf = new CountUp("books-to-shelf", 0, 34, 0, 5.5, options);
  var daysRead = new CountUp("days-read", 0, 12, 0, 5.5, options);
  var pagesRead = new CountUp("pages-read", 0, 12, 0, 5.5, options);
  var weekendsRead = new CountUp("weekends-read", 0, 4, 0, 5.5, options);

...
```
