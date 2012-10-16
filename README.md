<h2>Simple Grid</h2>
<h3>Intro</h3>
<p>Simple Grid is a basic lightweight grid, not a CSS framework. There are no styles for buttons, tables, typography etc. etc. Simple Grid comes with two different types of grids. There is a grid for content, which looks like <code>&lt;div class="col-1-3"&gt;&lt;/div&gt;</code> and a grid for layouts, which looks like <code>&lt;div class="col-4-12"&gt;&lt;/div&gt;</code>. Simple Grid is also built for responsive layouts. With fluid columns, the grid will resize to adjust to the browser resolution. To accomodate for mobile and tablet devices, the grid will essentially stack all columns, one above another, when viewed on smaller screens. </p>

<h3>Instructions</h3>
<p>In terms of use, Simple Grid is basically just like every other grid. Starting out, you need to wrap your grid in a div class named <code>grid</code>. If you want a 20px padding around your grid, add the class <code>grid-pad</code> to the div wrapper. Next, all you have to do is decide what size you want your grid to be and add the appropiate classes. For example, if you want a grid with a left sidebar and main content area you would do:
<pre>
&lt;div class="grid"&gt;
  &lt;div class="col-3-12"&gt;
  &lt;/div&gt;
  &lt;div class="col-9-12"&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
If you have a page and would like four columns of content, you would do:
<pre>
&lt;div class="grid"&gt;
  &lt;div class="col-1-4"&gt;
  &lt;/div&gt;
  &lt;div class="col-1-4"&gt;
  &lt;/div&gt;
  &lt;div class="col-1-4"&gt;
  &lt;/div&gt;
  &lt;div class="col-1-4"&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
The first column of content in your grid will always be floated left. If you would like to float a column to the right, all you have to do is add the class <code>push-right</code>.</p>

<h3>Preview</h3>
<p>To see the grid in action jump on over to the <a href="http://thisisdallas.github.com/Simple-Grid/" title="Simple Grid examples">Simple Grid example page</a>.</p>
