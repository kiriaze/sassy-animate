Animate.scss
============

A sassified animation version of Dan Edens Animate.css.

Import into project
`@import 'animate/animate';`

* Animation are imported with default variables set in _animate.scss.
* Properties defined within _properties.scss.
* Comment / Uncomment the animations you'd like to use.
* Set your own values in your _base.scss or wherever your variables are defined to override the default properties:

```
$duration: .35s;
$delay: .2s;
$delay: 0s;
$function: ease;
$fill: both;
$visibility: visible;
```

##License
Animate.scss is licensed under the GPL v2 license. (http://opensource.org/licenses/GPL-2.0)