# UI-UX-GradientBorder-RoundedTrxBox
If you run the border-box.html in a browser it will render a transparent box with gradient border and rounded corners.

A "gradient" border with smooth "border-radius" is achieved Using background-image and mask-composite property along with other helper properties.
We apply a gradient as background and we make its origin the border box (by default it's the padding box).
Using the mask property, we apply two opaque layers. The bottom one will cover the whole element and the top one will cover only the padding box (so it will not cover the border area).
We exclude the top layer from the bottom one so that only the border area will be shown!

You can adjust the border, gradient, and radius as you want. 

The only drawback is that this will mask the content so we can move the code to a pseudo-element instead.
We can also achieve any shape of box using "clip-path: polygon()", we have created innerbox polygon shape using plolygon function which
is also with gredient colour and border radius.
