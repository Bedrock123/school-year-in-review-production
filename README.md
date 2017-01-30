# School Review

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
    var days = new CountUp("days-read", 0, 362, 0, 12.5, options);
    var hours = new CountUp("hours-read", 0, 1925, 0, 12.5, options);
    var mins = new CountUp("avg-min-read", 0, 325, 0, 12.5, options);
    var weekends = new CountUp("weekends-read", 0, 118, 0, 12.5, options);
...
```
