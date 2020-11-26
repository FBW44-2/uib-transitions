# UIB Transitions

## Creating transitions

We will have 2 states: initial and end state. The end state is applied on hover.

You can start hiding the element after you are happy with the rest, otherwise it is difficult to see where the element is positioned.

## Some properties are cheaper to animate:

Prefer using `translate` instead of offset (`top`, `left`, `bottom`, `right`)

Prefer `scale` instead of `width` and `height`

## Hiding elements

Opacity will hide the element, but the element will remain interactive

Visibility will hide the element, but we cannot smoothly animate this property

Best is to use a combination of both