# Flexbox Cheatsheet

**`justify-content`**: this CSS property aligns items horizontally and accepts the following values:
* `flex-start`: Items align to the left side of the container, default value.
* `flex-end`: Items align to the right side of the container.
* `center`: Items align at the center of the container.
* `space-between`: Items display with equal spacing between them.
* `space-around`: Items display with equal spacing around them.

**`align-items`**: This CSS property aligns items vertically and accepts the following values:
* `stretch`: Items are stretched to fit the container, default value;
* `center`: Items align at the vertical center of the container.
* `baseline`: Items display at the baseline of the container.
* `flex-start`: Items align to the top of the container.
* `flex-end`: Items align to the bottom of the container.

**`flex-direction`**: This CSS property defines the direction items are placed in the container, and accepts the following values:
* `row`: Items are placed the same as the text direction, default value.
* `row-reverse`: Items are placed opposite to the text direction.
* `column`: Items are placed top to bottom.
* `column-reverse`: Items are placed bottom to top.
    
**`order`**:  we can apply the order property to individual items. By default, items have a value of 0, but we can use this property to also set it to a positive or negative integer value. 

**`align-self`**: Another property you can apply to individual items is align-self. This property accepts the same values as align-items and its value for the specific item.

**`flex-wrap`**: Spread the items using this property, which accepts the following values:
* `nowrap`: Every item is fit to a single line, default value.
* `wrap`: Items wrap around to additional lines.
* `wrap-reverse`: Items wrap around to additional lines in reverse.
 
**`flex-flow`**: The two properties `flex-direction` and `flex-wrap` are used so often together that the shorthand property flex-flow was created to combine them. This shorthand property accepts the value of one of the two properties separated by a space. Values:
    `<flex-direction property> <flex-wrap property>`

**`align-content`**: set how multiple lines are spaced apart from each other. This property takes the following values:
* `flex-start`: Lines are packed at the top of the container.
* `flex-end`: Lines are packed at the bottom of the container.
* `center`: Lines are packed at the vertical center of the container.
* `space-between`: Lines display with equal spacing between them.
* `space-around`: Lines display with equal spacing around them.
* `stretch`: Lines are stretched to fit the container.

_notes_: `align-content` determines the spacing between lines, while * `align-items` determines how the items as a whole are aligned within the container. When there is only one line, `align-content` has no effect.

--------------------------
source: https://flexboxfroggy.com/, all merits are due to them.