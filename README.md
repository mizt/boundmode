boundmode is Boundary handling mode

* 0 = ignore: Values that exceed the limits are ignored.
* 1 = clear: Values that exceed the limits are set to 0.
* 2 = wrap: Values that exceed the limits are wrapped around to the opposite limit with a modulo operation. (256 wraps to 0, 257 wraps to 1, and -1 wraps to 255, -2 wraps to 254, etc.)
* 3 = clip: Values are limited not to exceed min or max. (e.g. numbers greater than 255 are set to 255, and numbers less than 0 are set to 0.)
* 4 = fold: Values that exceed the limits are folded back in the opposite direction. (256 is folded back to 254, 257 is folded back to 253, and -1 is folded back to 1, -2 to 2, etc.)

##### Reference

[Jitter](https://cycling74.com/products/jitter)