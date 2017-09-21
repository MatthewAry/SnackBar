[![SnackBar](http://www.polonel.com/snackbar/logo_large.png)](http://www.polonel.com/snackbar)

A notification toast inspired by Google Material Design.

Getting Started
---------------

Installing Snackbar is as easy as...

```bash
bower install snackbar
```
or maybe you wish to use NPM...

```bash
npm install node-snackbar
```
and if that doesn't float you, you can always download the CSS and JS files...
```html
<script type="text/javascript" src="dist/snackbar.min.js"></script>
<link rel="stylesheet" type="text/css" href="dist/snackbar.min.css" />
```

Examples
--------
Checkout the [Demo page](http://www.polonel.com/snackbar).

Options
-------
| Key         | Type   | Default        | Description |
|-------------|--------|----------------|-------------|
| text        | String | `Default Text`   | The text to display inside the notification. |
| textColor   | String | `#ffffff`        | The color of the text inside of the notification. _Default color is white._ |
| pos         | String | `bottom-left`    | The location in the browser window where the notification will appear. <br>Options:<ul><li>bottom-center</li><li>bottom-left</li><li>bottom-right</li><li>top-left</li><li>top-center</li><li>top-right</li></ul> |
| customClass | String | `''` | Add a custom class to the notification for custom styling. |
| width | String | `auto` | The width of the notification. [Learn more about the width property.](https://developer.mozilla.org/en-US/docs/Web/CSS/width) |
| showActionButton | Boolean | `true` | Adds or removes the action button. |
| actionText | String | `Dismiss` | The action button's text. |
| actionTextColor | String | `#4caf50` | The action button's text color. |
| duration | Number | `5000` | The time (in milliseconds) the notification is displayed before it's removed. <br> Set this value to `0` to make persistent. |
| onActionClick | Function | `fadeOut` | Closes the notification by default. A function with the notification element as the argument |

TODO
----
* Make notifications stackable.
