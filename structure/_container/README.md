# Grid Containers

A grid container is an element which houses grid items, and possesses the `display: grid` declaration.

These containers are the very foundation of a grid layout, and once defined allow you to work in a grid formatting context.

### Configuration

All grid layouts start with a **grid container** - this is accomplished using the `display: grid` or `display: inline-grid` declarations.

**HTML**

```
<section class="grid-container"> ... </section>
```

**CSS**

```
.grid-container {
  display: grid;
}
```
Once defined, the container doesn't affect the layout of its grid items, a la flexbox, the layout only changes when the [rows](../rows) and [columns](../columns) are set.

---

#### References

- [Complete Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
