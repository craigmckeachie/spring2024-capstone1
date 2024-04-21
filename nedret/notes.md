- great project!

- a few validation issues existed that I fixed you can see in the diff

  - registration page had an unclosed div on the form
  - unique id validation rule broken on registration
  - button cannot be nested inside anchor in index.html

  This style is unnecessary because it is already included in the bootstrap stylesheet.
  Removing it did seems to have some effect on the design of the font-weight in the site.
  I will need to look into it.

  ```css
  * {
    font-family: sans-serif;
  }
  ```
