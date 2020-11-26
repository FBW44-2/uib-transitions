# UIB Transitions

## Some properties are cheaper to animate:

- transform instead of offset (top, left, bottom, right)
- scale instead of width and height

## Hiding elements

Opacity will hide the element, but the element will remain interactive

Visibility will hide the element, but we cannot smoothly animate this property

Best is to use a combination of both