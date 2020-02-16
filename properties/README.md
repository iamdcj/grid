# CSS Grid Property : Value list

#### display

The `display` property is used on containers in the following ways;

- `display: grid`
- `display: inline-grid`

#### grid-template-columns

The `grid-template-columns` property allows the engineer to state the number of columns, and their corresponding widths;

- `grid-template-columns: 200px 20px auto` - this will generate three columns, one at `200px` wide, the other `20px` wide, and the final column will take up whatever room it can on the x-axis.
-

#### grid-template-rows

The `grid-template-rows` property allows the engineer to state the number of rows, and their corresponding heights;

- `grid-template-rows: 200px 20px` - this will generate two rows, one at `200px` tall, the other at `20px` tall.

#### grid-auto-rows / grid-auto-columns

These properties allow the engineer to define the size for any implicit tracks, either column or row;

- `grid-auto-columns: 150px` - this sets any browser generated column to be `150px` wide.
- `grid-auto-rows: 200px` - this sets any browser generated row to be `200px` tall.

These rules accept multiple, space-separated values;

- `grid-auto-rows: 200px 150px` - this sets any browser generated row to be either `200px` or `150px` tall, based on the number of implicit rows, and the grid flow direction.

#### grid-auto-flow

The `grid-auto-flow` property allows the engineer to define how the items should 'flow', which tells the browser how to handle any implicit items in the grid.

The following example tells the browser not to wrap any implicit columns, i.e. don't generate a row, but simply keeping adding any items as a column, with a width of `200px`.

```
  grid-auto-flow: column;
  grid-aut-columns: 200px;
```

#### gap / grid-gap / grid-column-gap / grid-row-gap

These properties will set space between either the row, column, or both tracks;

- `grid-gap: 20px` - this sets a `20px` gap on both row and column tracks.
- `grid-column-gap: 20px` - this sets a `20px` gap on _just_ the column tracks.
