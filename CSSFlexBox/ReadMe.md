# FlexBox

-- It is the CSS FLexible Module or simply known as FlexBox is a one-dimensional layout model.

-- It allows you to design flexible and efficient layouts, align and distribute space among items in a container.

-- FlexBox helps you arrange elements in a web page with ease.

## Layout Modules Before Flexbox

-> Block, for sections in a webpage
-- Inline, for text
-- Table, for two-dimensional table data
-- Positioned, for explicit position of an element

## Why Flexbox?

-- a lot of flexibility
-- arrange items
-- space
-- alignment
-- order of items

## Terminology

-- Flex Container (Parent Container)
-- Flex Items (Child Items)

### Flexbox axes

-- Main Axis (runs left to right)
-- Cross Axis (perpendiular to main axis)(top to bottom)
-- The start point of main axis is Main start and end is Main end.
-- The length between them is called Main size.

-- Similarly,, for Cross Axis it is Cross Start and Cross End and Cross Size.

### Flex Container Properties

-- display (Defines a Flex Container and is mandatory)
-- flex-direction (Defines the direction in which the flex items are placed in the container)
-- flex-wrap (used to control wrapping of flex items within the container)
-- flex-flow (shorthand for flex-direction and flex-wrap)
-- column-gap (for gap between columns)
-- row-gap (for gap between rows)
-- gap (shorthand for column-gap and row-gap)
-- justify-content (defines the alignment of flex items along the main axis)
-- align-items (defines how flex items are aligned along the cross axis)
-- align-content (defines the alignment of flex items along the cross axis)

#### display

-- Used to create either a block level or inline level flex container.

-- The possible values are:
---- 1) flex 2) inline-flex

#### flex-direction

-- Sets the direction of the main axis.

-- The possible values are:
--- a) row (default) (left to right)
b) row-reverse (right to left)
c) column (top to bottom)
d) column-reverse (bottom to top)

#### flex-wrap

-- Used to control the wrapping of flex items within the container.

-- The possible values are:

---- a) nowrap (default)
b) wrap
c) wrap-reverse

#### flex-flow

--- Shorthand for flex direction and flex wrap

-- The possible values are:

---- a) flex-flow: <flex-direction><flex-wrap>

#### Gap properties

-- Specify the gap between columns using column-gap
-- Specify the gap between rows using row-gap
-- Specify both row and column gap using gap: <row-gap><column-gap>

-- Values can be a non negative value or percentage.

#### justify-content

-- Align items and distribute any extra spacing in the parent container. The alignment is always along the main axis.

-- The possible values are:

--- a) flex-start
b) flex-start
c) center
d) space-between
e) space-around
f) space-evenly

#### align-items

-- Aligh item along the cross axis.

-- The possible values are:

--- a) flex-start
b) flex-end
c) center
d) baseline
e) stretch (default)

#### align-content

--- Aligns lines of content along the cross axis and distribute any extra spacing in the parent container.

-- The possible values are:

--- a) flex-start
b) flex-end
c) stretch (default)
d) center
e) space-between
f) space-around

### Flex item properties

-- The possible values are:
-- 1) order 2) flex-grow 3) flex-shrink 4) flex-basis 5) flex 6) align-self

#### order

-- Controls the order of flex items container.

--Accepts an integer value.

-- Elements with the same order value are laid out in the order in which they appear in the source code.

#### flex-grow

-- Dictates what amount of the available white space inside the flex container the item should take up.
-- It is relative to the other items in the container.
-- Default value is 0 - items do not grow.
-- flex-grow value of 1 - flex items grow evenly.

#### flex-shrink

-- Dictates the shrink factor of the flex items when the default size of flex items is larger than the flex container.

-- Relative to the other items in the container.
-- Default value is 1.

#### flex-basis

-- Sets the initial size of a flex item.

-- Pixels, percentages or relative units

-- Default value is auto.

#### flex

-- Shorthand for flex-grow, flex-shrink and flex-basis.
-- flex: <flex-grow><flex-shrink><flex-basis>

#### align-self

-- ALign the items individually.
-- Values like auto, flex-start, flex-end, center and stretch.
-- Overrides the align-items value of the flex container.
