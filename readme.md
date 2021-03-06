![Lan Grid System Logo](http://joshnh.com/langrid/i/logo.png)

### Lan Grid System

##### Lightweight & Nestable

<hr>

__Website:__ http://joshnh.com/langrid

__Live demo:__ http://joshnh.com/grid-demo

__Blog post:__ http://joshnh.com/weblog/creating-lightweight-grid-system/

<hr>

##### Usage:

1. Set an element as a container by using the <code>grid</code> class.
2. Declare columns using <a href="http://getbem.com/introduction/">BEM syntax</a> (<code>grid__col--{width}</code>).
3. You're all done!

<hr>

##### Notes:

- You need to use block-level elements when declaring containers and columns.
- White space between columns needs to be commented out in your markup.
- To nest columns, simply use the <code>grid</code> class on each parent column.
- Keep your grid abstracted by using dedicated elements to avoid style conflicts.
- Read more about this grid system <a href="http://joshnh.com/weblog/creating-lightweight-grid-system/">here</a>.

<hr>

##### Example:

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
