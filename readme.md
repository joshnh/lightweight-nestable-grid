Lightweight Nestable Grid
=========================

__A lightweight, nestable, mobile first grid.__

To use the grid you will need a parent element with a class of `grid`. Columns are then implemented by using a class equal to the desired percentage width (`grid__col--{width}`). When nesting, you will need to use the `grid` class on each grid's parent. For best performance, keep your grid abstracted by using dedicated elements.

Also, and this is _important_, due to the use of inline-block you will need to comment out the white space between the column elements. This is the most consistent way to deal with this space.

The available widths are:

| Width | Class             |
| ----- | ----------------  |
| 20%   | `.grid__col--20`  |
| 25%   | `.grid__col--25`  |
| 30%   | `.grid__col--30`  |
| 33%   | `.grid__col--33`  |
| 40%   | `.grid__col--40`  |
| 50%   | `.grid__col--50`  |
| 60%   | `.grid__col--60`  |
| 67%   | `.grid__col--67`  |
| 70%   | `.grid__col--70`  |
| 75%   | `.grid__col--75`  |
| 80%   | `.grid__col--80`  |
| 100%  | `.grid__col--100` |

Example markup:

~~~
<div class="grid">
	<div class="grid  grid__col--67">
		<div class="grid__col--50">
			…
		</div><!--
	 --><div class="grid__col--50">
			…
		</div>
	</div><!--
 --><div class="grid__col--33">
		…
	</div>
</div>
~~~

Live demo: http://codepen.io/joshnh/pen/f2d2f034c97f4d6d89c47955c3b92f8d

_Note: make sure that you are using the `grid` and `grid__col--{width}` classes on block level elements._
