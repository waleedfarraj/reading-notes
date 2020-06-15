# Read: 08 - More CSS Layout
## My notes from the re-read of chapter 15 
- css is how you control the looks of your **html** .
- The element inside other elemnents are called child element and the outer element is the parent .
- In normal flow, each block-level element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow.
- You then use the offset 
properties (top or bottom and
left or right) to indicate how
far to move the element from
where it would have been in
normal flow.
- When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.) 
-Fixed positioning is a type
of absolute positioning that
requires the position property
to have a value of fixed.
It positions the element in
relation to the browser window.
Therefore, when a user scrolls
down the page, it stays in the
exact same place
-When you use relative, fixed, or
absolute positioning, boxes can
overlap. If boxes do overlap, the
elements that appear later in the
HTML code sit on top of those
that are earlier in the page.
If you want to control which
element sits on top, you can use
the z-index property. Its value
is a number, and the higher the
number the closer that element
is to the front. For example, an
element with a z-index of 10
will appear over the top of one
with a z-index of 5.
-The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
Anything else that sits inside
the containing element will
flow around the element that is
floated.
- you can use float to make pargraphs go next to each other by controloing the box dimensions,
width,margin,padding.The clear property allows you to say that no element (within
the same containing element) should touch the left or righthand sides of a box.

- When designing a web page you need to keep in mind the most if not all the sizes of the divces that the vistor's will be using . aswell as the resouloution .
-Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens).
- many designs still try to let the user know what the site is about within the top 570-
600 pixels, as well as hint at more content below this point.
But do not try to cram too much into that top area.
-  and again there is fixed with layouts and liquid width layouts .baiscally you can have more control in fixed layouts  and you have more fluidity in liquid layouts but not as much control whcich can make the page look clunky at times .
-Grids set consistent proportions
and spaces between items which
helps to create a professional
looking design. 