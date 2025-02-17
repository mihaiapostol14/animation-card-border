# Simple Animated Card Border With HTML & CSS

This CSS code creates a stylish card component with an animated glowing border effect. Below is a detailed breakdown of its elements and functionality:

### Global Styles
- Resets default margin and padding for all elements.
- Uses `box-sizing: border-box` to ensure elements respect their width and height.

### Body Styling
- Sets `display: flex` to center the `.card-container` both vertically and horizontally.
- Applies a dark background color (`#0B0D15`) to enhance the glowing effect of the card.

### Card Container
- Limits the maximum width to `400px` and height to `50%` of the viewport.
- Uses a dark theme (`#1c1f2b`) as the background for the card.
- Centers text within the card.
- Positions itself relative to allow pseudo-elements (`::before` and `::after`) to be positioned correctly.

### Text Styling
- The title (`.card-title`) and the text (`.card-text`) are colored white for contrast.
- The title is capitalized and has an increased font size of `1.5rem`.

### Animated Glowing Border Effect
- Defines `@property --angle` to handle the animation of the conic gradient.
- Uses `::after` to create a border with a conic gradient that cycles through various colors.
- The `::before` pseudo-element applies a blur effect for an additional glowing look.
- Implements `@keyframes spin` to rotate the gradient continuously, creating a dynamic glowing border effect.

Cloning project or download archive
```bash
git clone https://github.com/mihaiapostol14/animation-card-border.git
```


