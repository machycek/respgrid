Respgrid
=========

A simple grid for responsive websites

<h1>Introduction</h1>
<p>Respgrid is lightweight framework which helps you to build fully responsive websites.</p>
<p>Don't you like those responsive frameworks which includes almost everything, but you have never used most of their classes?</p>
<p>Me neither, so I made this simple grid.</p>

<h1>Classes</h1>
<p>Respgrid uses same classes like every other responsive framework do.</p>

<h4>Container class</h4>
<pre>&lt;div class="container"&gt;&lt;div&gt;</pre> 
<strong>This class tells the browser that container has specific width</strong>

<ul>
	<li>1170px on large screens</li>
	<li>992px on middle screens</li>
	<li>Ff device is smaller than 768px then 100% with</li>
</ul>

<h4>Row class</h4>
<pre>
	&lt;div class="container"&gt;
		&lt;div class="row"&gt;
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<strong>has attribute 100% with</strong>

<h4>Col classes</h4>
<pre>
	&lt;div class="container">
		&lt;div class="row">
			&lt;div class="col-6">&lt;/div&gt;
			&lt;div class="col-6">&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<strong>Col-6 tell the browser to be 6/12(50%) width</strong>
<br>
<strong>You can also use there classes like</strong>
<pre>
	&lt;div class="container"&gt;
		&lt;div class="row"&gt;
			&lt;div class="col-4">&lt;/div&gt;
			&lt;div class="col-4">&lt;/div&gt;
			&lt;div class="col-4">&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<strong>Col-4 tell the browser to be 1/3(33.3%) width</strong>
<strong>There are classes from col-1 to col-12</strong>
<ul>
	<li>.col-1 - width: 1/12</li>
	<li>.col-2 - width: 2/12</li>
	<li>.col-3 - width: 3/12</li>
	<li>...</li>
</ul>

<h4>Offset classes</h4>
<pre>
	&lt;div class="container">
		&lt;div class="row">
			&lt;div class="col-4">&lt;/div&gt;
			&lt;div class="offset-2 col-6">&lt;/div&gt;
		&lt;/div&gt;
	&lt;/div&gt;
</pre>
<strong>offset-2 class tells the browser to set margin-left 2/12(16.6%) width</strong>
<strong>Offsets and Col classes in every row couldn't be more that 12</strong>
<strong>There are classes from col-1 to col-12</strong>
<ul>
	<li>.offset-1 - margin-left: 1/12</li>
	<li>.offset-2 - margin-left: 2/12</li>
	<li>.offset-3 - margin-left: 3/12</li>
	<li>...</li>
</ul>


<h4>Position classes</h4>
<strong>center - centers the element</strong>
<pre>
	&lt;div class="center"&gt;&lt;/div&gt;
</pre>
<strong>Push-right - float the element to right</strong>
<pre>
	&lt;div class="push-right"&gt;&lt;/div&gt;
</pre>
<strong>Push-left - float the element to left</strong>
<pre>
	&lt;div class="push-left"&gt;&lt;/div&gt;
</pre>
<strong>tac - align text to center</strong>
<pre>
	&lt;div class="tac"&gt;&lt;/div&gt;
</pre>
<strong>tal - align text to left</strong>
<pre>
	&lt;div class="tal"&gt;&lt;/div&gt;
</pre>
<strong>tar - align text to right</strong>
<pre>
	&lt;div class="tar"&gt;&lt;/div&gt;
</pre>



<h4>Visible classes</h4>
<strong>Visible only on large devices</strong>
<pre>
	&lt;div class="visible-lg"&gt;&lt;/div&gt;
</pre>
<strong>Visible only on medium devices</strong>
<pre>
	&lt;div class="visible-md"&gt;&lt;/div&gt;
</pre>
<strong>Visible only on small devices</strong>
<pre>
	&lt;div class="visible-sm"&gt;&lt;/div&gt;
</pre>
<strong>Show - shows element</strong>
<pre>
	&lt;div class="show"&gt;&lt;/div&gt;
</pre>
<strong>Hide  - hides element</strong>
<pre>
	&lt;div class="hide"&gt;&lt;/div&gt;
</pre>

<h4>Clearfix class</h4>
<strong>clears all the floats</strong>
<pre>
	&lt;div class="clearfix"&gt;&lt;/div&gt;
</pre>

<h4>Sass center mixin</h4>
<strong>Centers the element by entered conditions</strong>
<strong>center the element horizontally</strong>
<p>@include center(x)</p>
<strong>center the element vertically</strong>
<p>@include center(y)</p>
<strong>center the element horizontally and verticaly</strong>
<p>@include center(xy)</p>









