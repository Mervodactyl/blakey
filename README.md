# My name is blakey.

I represent [Roi](http://github.com/roidriscoll) and [Mervé's](http://github.com/Mervodactyl) first foray into __Vertical Rhythm__.


![portrait of Art Blakey](http://berta11.express.ge/ZoneB/12/performer//Art%20Blakey/.photo/arblakey2.jpg)

[Normalise.css](https://necolas.github.io/normalize.css/) is WAS NOT compatible within the confines of vertical rhythm therefore we choose to use the [Meyer-reset](http://meyerweb.com/eric/tools/css/reset/) in this example

### The key to Vertical Rhythm is that all elements must take up a height of ( n * base line-height ) where 'n' is an integer value

Therefore __SASS mixins__ are ideal for calculating the necessary font-sizes and line-heights

By setting body { font-size: 100%; } it means that the browser will automatically render the font to their default font-size (usually 16px)
