# Simple Animated Card Border With HTML & CSS

This repository contains a stylish card component with an animated glowing border effect created using CSS and HTML.

## Project Overview

The project demonstrates how to create a card component with an animated glowing border effect. The card is styled using CSS to provide a visually appealing look and feel. The project showcases various CSS techniques, including pseudo-elements, conic gradients, and keyframe animations.

## Features

- **Global Styles**: Resets default margin and padding for all elements, and uses `box-sizing: border-box` to ensure elements respect their width and height.
- **Body Styling**: Centers the `.card-container` both vertically and horizontally, and applies a dark background color (`#0B0D15`) to enhance the glowing effect of the card.
- **Card Container**: Limits the maximum width to `400px` and height to `50%` of the viewport, uses a dark theme (`#1c1f2b`) as the background for the card, centers text within the card, and positions itself relative to allow pseudo-elements (`::before` and `::after`) to be positioned correctly.
- **Text Styling**: Styles the title (`.card-title`) and the text (`.card-text`) in white for contrast, capitalizes the title, and increases the font size to `1.5rem`.
- **Animated Glowing Border Effect**: Defines `@property --angle` to handle the animation of the conic gradient, uses `::after` to create a border with a conic gradient that cycles through various colors, applies a blur effect with `::before` for an additional glowing look, and implements `@keyframes spin` to rotate the gradient continuously, creating a dynamic glowing border effect.

## File Structure

The project consists of the following files:

- `index.html`: Contains the HTML structure of the card component.
- `styles.css`: Contains the CSS styles for the card component, including the global styles, body styling, card container, text styling, and the animated glowing border effect.

## Usage

To use this project locally, clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/mihaiapostol14/animation-card-border.git
cd animation-card-border
open index.html
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## Contact

For any questions or inquiries, please contact [mihaiapostol14](https://github.com/mihaiapostol14).
