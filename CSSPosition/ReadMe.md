# Position

5 different values of position in CSS

- static: (by default, elements are positioned according to normal flow of the page)

- relative: (is positioned relative to its normal position)
  (can be controlled using property top, left, right and bottom)

- fixed: (positions an element relative to the viewport)
  (if we want something to be fixed no matter we scroll our page,
  the element can be controled by top, bottom, left and right
  eg: Feedback or chat bot button always positioned botton right

- absolute: elemenet will be absolute but within relative to its parent(absolute with relative to its parent)

- sticky: positioned based on the user's scroll position, moves along with the scroll.
  eg: on a webpage, if we want that element that need to be on the normal layout of the page
  and always visible as we scroll, position: sticky is very useful

## 2 main categories of css units

- Absolute unit : Generally considered to always be the same size, useful for the layouts where the page needs to be printed. eg: px
- Realtive unit : They are relative to something else,perhaps the size of the parent elemet's font
  or the size of the viewport. eg: em, rem, vw, vh etc

- rem : relative to the font size of the parent element i.e body.
  1 rem = 16px (font-size of body by default)

- vh : height relative to the viewport. eg: 5ovh will be 50% of the viewport width
- vw : width relative to the viewport. eg: 50vw will be 50% of the viewport width

- 3 types of math function that can be used as property value

- calc()
- max()
- min()
