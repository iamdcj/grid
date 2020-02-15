# Lines

A line runs before, between or after a column or row.

### Line Types

There are two types of lines in a grid layout; row lines and grid lines.

#### Row Lines

A row line exists either side of the items in a row track.

```
------------
[][][][][][]
------------
```

#### Column Lines

A column line exists either side of the items in a column track.

```
|[]|
|[]|
|[]|
|[]|
```

### Counting Lines

There will always be one line extra than the number of columns/rows.

```
------------
[][][][][][]
------------
```

The above contains a single row track, but **two** lines, one before, one after - this is always the case, regardless of the number of tracks; one before the first track, and one after every track thereafter.
