
We will be reusing project files from last time.

Start by editing the **grid-flex.html** and **grid-flex.css** files in this repo. Add the style code at the end of the file.

We will be building the layout in **layout2.png**, using a combination of grid and flexbox.

Inside of body, add a div with id "body-container";

 - create a header tag
   - create an h1 tag with text "Header" inside the header tag. Make sure the Header text is centered.
 - create a nav tag
   - add 4 links to the nav tag, with links to: /index.html, /form.html. /grid.html, /login.html
   - make sure the links are evenly spaced out. You can use flexbox for the nav tag.
 
 
 - create an "article-container" div tag, with display flex, direction row.
   - create an aside tag
     - create an unordered list of 5 elements, each with text Item 1 - 5 inside of it

   - create a "content-container" inside the "article-container" tag, where we'll place a "content" div and a section.
   - make "content-container" display flex, direction column
     - add 3 images inside of the content tag, with width and height 100px, source assets/image1.png.
       - make them spaced out evenly inside their parent;

 - create a footer tag, with an h4 tag with text "Footer" inside of it. Make sure the Footer text is centered

Style the "body-container" div:
 - background-color #c4ebf9
 - add padding: 35px;
 - make it display grid.
 - define your columns and rows using grid-template-columns and grid-template-rows
  - header, navigation and footer should be of height 60px
  - add a gap between the items in the grid, using gap, of 30px;

Header, footer should have background-color #03bfb1;

Aside should have background color #6edb6e;

Content div tag should have background color #0f98c6;

Section tag should have background color #005b92;






