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

## *object-fit*
> **The object-fit property defines how an element responds to the height and width of its content box. It’s intended for images, videos and other embeddable media formats in conjunction with the object-position property. Used by itself, object-fit lets us crop an inline image by giving us fine-grained control over how it squishes and stretches inside its box.**

* ***fill***(default):  stretches the image to fit the content box, regardless of its aspect-ratio

* ***contain***: increases or decreases the size of the image to fill the box whilst preserving its aspect-ratio 

* ***cover***: the image will fill the height and width of its box, once again maintaining its aspect ratio but often cropping the image in the process

* ***none***: image will ignore the height and width of the parent and retain its original size

* ***scale-down***: image will compare the difference between none and contain in order to find the smallest concrete object size.

## *gap*
defines the size of the gap between the rows and between the columns in flexbox, grid or multi-column layout
* shorthand for the *row-gap* and *column-gap* property

```css
gap: 20px 50px; 
/*gap of 20 px in row and 50 px in column (both grid and flexbox)*/
```

## *pseudo-element*
  *pseudo element is not an exclusive property of flexbox but this is one of the most important properties used in css.*

* is used to : 
  * style specified parts of an element
  * insert content ***before***, or ***after***, the content of an element

  ### syntax
  ``` css
  selector::pseudo-element {
  property: value;
  }
  ```

* all the pseudo-elements used in CSS are listed below:
  
    * ***after:*** insert something after the content of the element
    * ***before:*** insert something before the content of the element
    * ***first-letter:*** selects the first letter of the element
    * ***first-line:*** selects the first-line of the element
    * ***marker:*** selects the markers of list items 
    * ***selection:*** selects the portion of an elemnent that is selected by a user. 


#### *This concludes my Flexbox learning journey. Thank you for visiting my github and reading and using it all along.*
