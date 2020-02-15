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

#### gap / grid-gap / grid-column-gap / grid-row-gap

These properties will set space between either the row, column, or both tracks;

- `grid-gap: 20px` - this sets a `20px` gap on both row and column tracks.
- `grid-column-gap: 20px` - this sets a `20px` gap on _just_ the column tracks.
