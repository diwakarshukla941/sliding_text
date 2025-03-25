# Infinite Scroll Animation

## Description
This project showcases an infinite horizontal scrolling animation for text and images using HTML, CSS, and simple keyframe animations. It creates a visually appealing effect where the content continuously moves from right to left.

## Features
- Smooth infinite scrolling effect
- Multiple scrolling speeds for different sections
- Hover effect on text elements
- Supports both text and image scrolling
- Responsive design with a gradient mask effect

## Technologies Used
- HTML
- CSS

## How It Works
- The scrolling effect is achieved using CSS animations (`@keyframes`).
- Two child `<div>` elements inside each `.scroll` container create a seamless looping effect.
- The `animation-delay` ensures the second block starts at the right moment for a continuous scroll.
- A gradient mask is applied using `-webkit-mask-image` to fade the edges smoothly.

## Installation
1. Clone the repository or download the source files.
   ```sh
   git clone https://github.com/diwakarshukla941/sliding_text
   ```
2. Open `index.html` in your browser.

## Customization
- Adjust the scrolling speed by modifying the `--time` variable in the inline `style` attributes.
- Change the content inside the `<span>` elements for text-based scrolling.
- Update the images in the `imgBox` section to display different icons.

## Demo
Open `index.html` in a browser to see the infinite scrolling animation in action.

## License
This project is open-source and available for personal and commercial use.

## Author
[Your Name]

