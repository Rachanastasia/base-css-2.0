# Base CSS for Mobile First Development

This file is meant as a starting point for CSS. It sets up varaibles and styles DOM elements for mobile first development.

## globals.css

This file contains all CSS variables for the project.

### Color

- Accent (--colors-accent)
- Light variant (--colors-accent-light)
- Dark variant (--colors-accent-dark)
- Black (--colors-black)
- White (--colors-white)

### Spacer

- Tiny (--spacer-tiny)
- Small (--spacer-sm)
- Medium (--spacer-med) \*
- Large (--spacer-lg) \*

\* increases at 800px

### Font

- Small (--font-size-sm)
- Medium (--font-size-med)
- Large (--font-size-lg)

- Line spacing (--line-spacing)

- Font Family (--font)

### Button

- Width (--button-width)
- Height (--button-height)
- Border radius

## rachel.css

### Header

Sets up as as flex box with title and button stacked in mobile and justified space between on larger screens. Header is --button-width tall. 

### Section

Sets up as flex column that is meant to be the immediate child of main. It limits width and has small padding.

### Form

Sets up label and input next to each other and aligns form elements. Styles the form button with custom buttons styles.

### Footer

Sets up a footer with icons that function as links that are spaced evenly.
