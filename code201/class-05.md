# Reading 05

## HTML Media

### Using the `alt` tag

The `alt` tag is useful for accessibility. This can be for screenreaders, or in the case where the source of the image changes or is invalid. If the image cannot be rendered, it will be replaced in the document by the text of the `alt` tag. This also helps in the case of slow Internet connections/large images with long render times.

### Improving image accessibility

You can use `alt` text as described above. Or, you can describe the image in the surrounding elements. You should not do both, however, because this is repetitive. If there is a description in a surrounding element, you should supply a blank `alt` tag like so: `<img src="foo" alt="">`

### Difference between GIF and SVG

GIFs and SVGs are types of picture files. They can display the same images but may appear differently based on the context in which they are used. GIFs might be blurry if they are displayed at the wrong resolution, which is the relationship between their width and height on a page/display. Image how a painting would look if all the details were squeezed onto a smaller canvas. SVGs on the other hand do not have this constraint. Their resolution scales depending on the size of their display. They will never blur.

### Using a screenshot on a page

It would be best to use an SVG because it scales, and screenshots are often taken on mobile devices, but could be viewed on a computer.

## Learn CSS

### Foreground vs background color

Have you ever looked at a colorful banner? Usually, the color of the text on the banner has a good contrast with the background. If it doesn't the text can be difficult or impossible to read. Foreground color is the color of the text in the context of CSS/HTML. Background color is the banner itself, or the body of a webpage, etc.

### Improving a friend's website

I would start with the major elements of the site. Background color might be a good first option for improvement, but also adding color and emphasis to certain text, like headers, could be useful. 

### Font considerations

Font choice affects readability. You don't want to sacrifice this in favor of some otherwise useless aesthetic consideration, or because the font suits your taste. Ideally, it could balance these two, but it is better to favor accessibility when it comes to web design.

### What CSS declarations do to HTML elements

Fonts are modified by CSS declarations like `font-style`, `font-width`, and `font-height`. These modify how the text appears on the page, making it bigger or smaller, and in a different typeface.

### Changing word spacing

You can use the `letter-spacing` or `word-spacing` properties in your CSS to change how text is spaced in a a heading element.
