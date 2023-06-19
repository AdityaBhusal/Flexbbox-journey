# flexbox
> this is my journey as a learner of CSS flexbox. it is not a ideal document that everyone should follow but the documentation of my flexbox journey.I took the  important topics and summarized in this documentation.

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

**row** (default) - horizontal axis with flex items from left to right.

**row-reverse** - horizontal axis with flex items from right to left.

**column** - vertical axis with flex items from top to bottom.

**column-reverse** - vertical axis with flex items from bottom to top.

>Note: The axes and directions will be different depending on the text direction. The values shown are for a left-to-right text direction.

## *flex-wrap*
>determines how your flex items behave when the flex container is too small
*  *wrap* - allows the items to wrap to the next row or column
*   *nowrap **(default)*** - prevents your items from wrapping and shrink them if needed.

## *justify-content*
  >determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them
* *center* - aligns the space around it to make the content in the center of the page
  
## align-items
> positions the flex content along the cross axis

* *normal	**(default)*** - behaves like
* *stretch* - items are stretched to fit the container
* *center* - items positioned at center of the flexbox container
* *flex-start* - items positioned at the beginning of the container
* *flex-end* - items positioned at the end of the container
* *start* - items positioned at the beginning of their individual grid cells, in block direction
* *end* - items positioned at the end of their individual grid cells, in block direction
* *baseline* - items positioned at the baseline of the container
* *initial* - sets the property to default value
* *inherit* - inherits the property from parent element