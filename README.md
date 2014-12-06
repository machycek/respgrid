Simple grid
=========

Simple grid for responsive websites

<h1>Introduction</h1>
<p>Respgrid is leightweight framework which helps you to build fully responsive website.</p>
<p>Don't you like those responsive frameworks which includes almost everything, but you have never used a tons of their classes?</p>
<p>Me neither so I made this simple grid.</p>

<h1>Classes</h1>
<p>Respgrid uses same classes like everyother responsive framework do.</p>

<h4>Container class</h4>
<pre>&lt;div class="container"&gt;&lt;div&gt;</pre> 
<h4>This class tells the browser that container has specific width</h4>

<ul>
	<li>1170px on large screens</li>
	<li>992px on middle screens</li>
	<li>Ff device is smaller than 768px then 100% with</li>
</ul>

<h4>Row class</h4>
<pre>
	&lt;div class="container">
		&lt;div class="row">
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<h4>has attribute 100% with</h4>

<h4>Col classes</h4>
<pre>
	&lt;div class="container">
		&lt;div class="row">
			&lt;div class="col-6">&lt;/div&gt;
			&lt;div class="col-6">&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<h4>Col-6 tell the browser to be 50% width of row</h4>
<br>
<h4>You can also use there classes like</h4>
<pre>
	&lt;div class="container">
		&lt;div class="row">
			&lt;div class="col-4">&lt;/div&gt;
			&lt;div class="col-4">&lt;/div&gt;
			&lt;div class="col-4">&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<h4>Col-4 tell the browser to be 1/3(33.3%) width of browser</h4>
<h4>There are classes from col-1 to col-12</h4>
<ul>
	<li>.col-1 - 1/12 width</li>
	<li>.col-2 - 2/12 width</li>
	<li>.col-3 - 3/12 width</li>
	<li>...</li>
</ul>









