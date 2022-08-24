# Reading 08

## Flexbox model

The flexbox model in CSS excels in one-dimensional layouts. This means that adjacent elements like a content body and a sidebar will be laid out side-by-side, and not on top of each other. This CSS model can be used to flexibly arrange elements that would otherwise overlap or compete for space given constraints on the viewport size.

## Main and cross axis

In the flexbox model, the main axis corresponds to the value of the `flex-direction` property. This can be either `row` or `column`. Depending on its value, the elements laid out in this model will move either horizontally or vertically when rearranged. If the main access is `row`, then the cross axis is `column`.

## Flexbox and accessibility

Flexbox modifies the visual order of the page's elements and not its logical order. Screen readers use the logical order to interpret the page and this can affect a user's understanding negatively.

## Flexbox vs. float

Traditional browser layout methods like float and positioning have limited possible applications. Positioning sub-elements within their parents is difficult or impossible with these tools. Likewise, filling containers with sub-elements and sizing them dynamically to fit these containers is challenging. The flexbox model enables this use case, often with a single declaration.

Flexbox seems like it will be an essential tool for me. Up to now, I have found positioning to be the single most frustrating element of writing CSS, and the box model a bit obscure without it. Now that I have this tool in my kit, I feel free to explore all the possibilities CSS has to offer me.
