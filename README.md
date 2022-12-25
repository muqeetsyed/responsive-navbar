# Responsive Navigation Bar `Notes`


## Concept of css display property:

Display property defines how to display an element in the UI.
Most elements by default has inline or block property.

Block-level Elements: A block-level element always starts on a new line and takes up the full width available.
Inline Elements: An inline element does not start on a new line and only takes up as much width as necessary.

Hiding an element can be done by setting the display property to none.

visibility:hidden; also hides an element.

However, the element will still take up the same space as before.

Display: inline-block allows us to set a width and height on the element, and it does not start on a new-line. i.e
it does not allow line break after the end of an element.

## Transition:
CSS transitions allows us to change property values smoothly, over a given duration.

## Transform:
The transform property applies a 2D or 3D transformation to an element. 

## Toggle:
The toggle() method toggles between hide() and show() for the selected elements. 
This method checks the selected elements for visibility. 
show() is run if an element is hidden. hide() is run if an element is visible - This creates a toggle effect.

##
The position property specifies the type of position used for an element.

<strong>Note:</strong> top,left,right,bottom are the positioning property whereas margin.....are  element's own property.

<strong>Types</strong>

#### static:
  By default, elements are static there is no effect of top, bottom, left, right.It has a normal position.

#### relative:
  It's position is relative to its normal position.
Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. 
Other content will not be adjusted to fit into any gap left by the element.

#### fixed:
  It's position is relative to the viewport, which means it always stays in the same place even if the page is scrolled.
The top, right, bottom, and left properties are used to position the element.

#### absolute: 
  An element with position: absolute; is positioned relative to the nearest positioned ancestor.
However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

#### sticky: 
  An element with position: sticky; is positioned based on the user's scroll position.
A sticky element toggles between relative and fixed, depending on the scroll position.


