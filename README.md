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

<h3>Push-Classes</h3>
<p>To push a column to the right, you can use the <code>push-X-X</code> classes:
<pre>
&lt;div class="grid"&gt;
  &lt;div class="col-1-3 push-1-3"&gt;
  &lt;/div&gt;
  &lt;div class="col-1-3 "&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
</p>

<h3>Mobile</h3>
<p>If you don't want to stack all columns on mobile and tablet you can simply add a extra class to each column:
<pre>
&lt;div class="grid"&gt;
  &lt;div class="col-1-3 mobile-col-1-2"&gt;
  &lt;/div&gt;
  &lt;div class="col-1-3 mobile-col-1-2"&gt;
  &lt;/div&gt;
  &lt;div class="col-1-3 hide-on-mobile"&gt;
  &lt;/div&gt;
&lt;/div&gt;
</pre>
To hide a element (column, div, a, etc.) on mobile and tablets you can add the class <code>hide-on-mobile</code> to it.
</p>

<h3>Preview</h3>
<p>To see the grid in action jump on over to the <a href="http://thisisdallas.github.com/Simple-Grid/" title="Simple Grid examples">Simple Grid example page</a>.</p>

<h3>Copyright & License</h3>

<p>Copyright (C) 2013 Dallas Bass - Released under the MIT License.</p>

<p>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:</p>

<p>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.</p>

<p>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>
