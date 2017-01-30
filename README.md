# School Review

[View the live demo](http://la-school-review.netlify.com/)

--------------------------------------------------------------------------------

All of the first name instances are labeled as:

```html
<!-- Learning Ally Member Frist Name -->
<span id=“first-name”>Carlos</span>

...
```

<span id="firt-name">&lt;/span</span>

For the numbers in the statistics bar I am using CountUp.Js for the effect. The Count Up Variables are defined in the inline footer script at the bottom of the page.

You will have to change the 362 here. The one inside of the html element is overridden by countup, but I would input it there as well incase countup fails.

```javascript
// CountUp.JS Configuration
    var days = new CountUp("days-read", 0, 362, 0, 12.5, options);
    var hours = new CountUp("hours-read", 0, 1925, 0, 12.5, options);
    var mins = new CountUp("avg-min-read", 0, 325, 0, 12.5, options);
    var weekends = new CountUp("weekends-read", 0, 118, 0, 12.5, options);
...
```
