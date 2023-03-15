# Flexbox


## Flex Container
The container is the parent element that contains a set of flex items. To create a flex container, set the `display` property of the parent element to `flex` or `inline-flex`.

## Flex Items
Flex items are the child elements inside the flex container. They can be any HTML element, and each item can have its own unique properties. Flex items are arranged in a single line, called the "main axis", and a perpendicular line, called the "cross axis".

## Flex Direction
The `flex-direction` property determines the direction of the main axis. It can be set to `row` (the default), `row-reverse`, `column` or `column-reverse`.

## Justify Content
The `justify-content` property aligns items along the main axis. It can be set to `flex-start` (the default), `flex-end`, `center`, `space-between`, `space-around`, or `space-evenly`.

## Align Items
The `align-items` property aligns items along the cross axis. It can be set to `stretch` (the default), `flex-start`, `flex-end`, `center`, `baseline`, or `first baseline`.

## Align Content
The `align-content` property aligns the space between the flex lines. It can be set to `stretch` (the default), `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, or `space-evenly`.

## Flex Grow, Shrink, and Basis
The `flex-grow`, `flex-shrink`, and `flex-basis` properties are used to set the size of the flex items. `Flex-grow` determines how much the item grows relative to the other items, `flex-shrink` determines how much the item shrinks relative to the other items, and `flex-basis` sets the initial size of the item.

## Flex Wrap
The `flex-wrap` property determines whether the flex items are forced onto a single line or can wrap onto multiple lines. It can be set to `nowrap` (the default), `wrap`, or `wrap-reverse`.

## Flex Flow
The `flex-flow` shorthand property combines the `flex-direction` and `flex-wrap` properties into a single declaration.

## Order
The `order` property determines the order in which the flex items appear within the container. Items with a lower order value appear first.

# Flexbox

- Flexbox is a one-dimensional layout model that allows you to create flexible and responsive layouts.
- Flexbox works along a main axis and a cross axis.
- The main axis is defined by the `flex-direction` property, which can have values of `row`, `row-reverse`, `column`, or `column-reverse`.
- The cross axis is perpendicular to the main axis.
- The children of a flex container are called flex items.
- The `display` property of the parent container must be set to `flex` in order to create a flex container.
- The `justify-content` property is used to align items along the main axis.
- The `align-items` property is used to align items along the cross axis.
- The `flex-wrap` property is used to wrap items onto multiple lines if they can't all fit in a single line.
- The `flex` property is a shorthand property that allows you to set the `flex-grow`, `flex-shrink`, and `flex-basis` properties in a single line.
- The `flex-grow` property specifies how much the flex item should grow relative to the other items in the container.
- The `flex-shrink` property specifies how much the flex item should shrink relative to the other items in the container.
- The `flex-basis` property specifies the initial size of the flex item before any available space is distributed.
- The `align-self` property is used to align a single flex item along the cross axis.
- Flexbox is supported by all modern browsers and has good support on mobile devices.

# CSS Layout


## Floats

- Floats allow us to move an element to the left or right of its container, which can be useful for creating columns or wrapping text around an image.
- Floats can be tricky to work with, especially when it comes to clearing them so that subsequent elements don't wrap around them.
- Floats are being phased out in favor of newer layout techniques like Flexbox and CSS Grid.

## Positioning

- Positioning allows us to place an element at a specific location on the page, relative to its containing element or to the browser window itself.
- There are four types of positioning: static, relative, absolute, and fixed. Each type has its own rules for how it's positioned and how it affects other elements on the page.
- Positioning can be useful for creating overlays, tooltips, and other UI elements that need to be positioned precisely.

## Flexbox

- Flexbox is a relatively new layout technique that allows us to create flexible, responsive layouts with a minimum of fuss.
- With Flexbox, we define a container element as a "flex container" and then set the layout properties of its children elements to determine how they should be arranged.
- Flexbox is especially useful for creating responsive designs that work well on different screen sizes.

## CSS Grid

- CSS Grid is another new layout technique that allows us to create complex, multi-column layouts with a high degree of control.
- With CSS Grid, we define a grid container and then place its child elements on specific grid "tracks" to create the layout we want.
- CSS Grid is particularly useful for creating magazine-style layouts, as well as more complex, multi-layered designs.

Flexbox is designed for one-dimensional content, meaning it arranges content in a single line.

The main axis is the line along which flex items are arranged, either horizontally or vertically, while the cross axis is perpendicular to the main axis.

Certain properties of flexbox, such as order, can negatively impact accessibility when the visual order is not the same as the logical order.

Advantages of using flexbox over float include easier centering of content, automatic equalizing of container heights, and better support for responsive design.

I may be able to use flexbox to create a boggle / tangleword clone I am working on.  However, I think that the grid system may be better.