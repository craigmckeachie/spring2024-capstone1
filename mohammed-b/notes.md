- html files should not be in Pages folder, should be at the root of the project
- all folder and filenames should be lowercased, for example Pages folder should be pages
- extra course files from demos earlier in the week mixed in with Capstone project
- should have one global stylesheet for shared styles to create consistent look on site
  - additional stylesheets are reasonable for page specific styles
- prettier code formatter needed to be run on all files
- casing of items in navigation inconsistent: some first letter uppercase, some first letter lowercase
- index.html had no html validation errors
- checkout.html had 12 html validation errors reported but only required two fixes
  - doctype should be uppercase (DOCTYPE)
  - `<input type="text" id="expyear" name="expyear" placeholder="2018"required>` needs space before required
  - unnecessary blank lines
- products.html had 7 html validation errors
  - doctype should be uppercase (DOCTYPE)
  - page had no title
  - Duplicate ID “cardImage” error because used on more than one element, caused 5 errors
- register.html had no html validation errors
- in general it looks like not much effort and time was spent on the site...this should represent 24-28 hours of work

## Design

- whitespace needed in many places
  - products,checkout,login touch the navigation at the top of the page..they need room to breathe
- Again, inconsistent casing in the navigation items
- bootstrap style classes applied on register page but not on the login page so it looks unfinished and inconsistent
- bullet points on home page overlapping and unreadable
- product images all different sizes and one doesn't load
