# flexbox

 Flexbox is a one-dimensional CSS layout that can control the way items are spaced out and aligned within a container.

To use it, give an element a display property of flex. This will make the element a flex container. Any direct children of a flex container are called flex items.

Example: 
```html
    *{
        display: flex; 
    }
```
## *flex-direction*
Flexbox has a main and cross axis. The main axis is defined by the *flex-direction* property, which has four possible values:

**row** (default): horizontal axis with flex items from left to right.

**row-reverse**: horizontal axis with flex items from right to left.

**column**: vertical axis with flex items from top to bottom.

**column-reverse**: vertical axis with flex items from bottom to top.

>Note: The axes and directions will be different depending on the text direction. The values shown are for a left-to-right text direction.

## *flex-wrap*
* determines how your flex items behave when the flex container is too small
*  *wrap* - allows the items to wrap to the next row or column
*   *nowrap **(default)*** prevents your items from wrapping and shrink them if needed.

## *justify-content*
*