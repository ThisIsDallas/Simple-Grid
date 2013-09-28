# Simple Grid

## Intro
Simple Grid is a basic lightweight grid, not a CSS framework. There are no styles for buttons, tables, typography etc. etc. Simple Grid comes with two different types of grids. There is a grid for content, which looks like `<div class="col-1-3"></div>` and a grid for layouts, which looks like `<div class="col-4-12"></div>`. Simple Grid is also built for responsive layouts. With fluid columns, the grid will resize to adjust to the browser resolution. To accomodate for mobile and tablet devices, the grid will essentially stack all columns, one above another, when viewed on smaller screens.

## Instructions
In terms of use, Simple Grid is basically just like every other grid. Starting out, you need to wrap your grid in a div class named `grid`. If you want a 20px padding around your grid, add the class `grid-pad` to the div wrapper. Next, all you have to do is decide what size you want your grid to be and add the appropiate classes. For example, if you want a grid with a left sidebar and main content area you would do:

````
<div class="grid">
  <div class="col-3-12">
  </div>
  <div class="col-9-12">
  </div>
</div>
````

If you have a page and would like four columns of content, you would do:

````
<div class="grid">
  <div class="col-1-4">
  </div>
  <div class="col-1-4">
  </div>
  <div class="col-1-4">
  </div>
  <div class="col-1-4">
  </div>
</div>
````

The first column of content in your grid will always be floated left. If you would like to float a column to the right, all you have to do is add the class `push-right`

## Preview
To see the grid in action jump on over to the [Simple Grid example page](http://thisisdallas.github.com/Simple-Grid/).
