# CSS Structure: Custom Properties

The CSS code in this challenge has multiple references to three different colors. Make use of custom properties (variables) to extract them.

## Task

Check the `./css/styles.css` file and find the three colors that are used multiple times. Unfortunately not all references to the same color use the same syntax.

Create a new `:root` selector and define three custom properties (variables) for the three colors. Use the following property names:

- "--color-black-light" for the light black
- "--color-primary" for the violet
- "--color-white" for the white

> 💡 Use a consistent `--color-<name>` naming for your properties.  
> Make sure that all colors use the same syntax (e.g. hex `#ffffff` or `rgb()`).

Replace all references to the colors with the custom properties (variables) you have created.

Make sure that everything still looks the same as before.

> 💡 Use the [CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) (`var()`) syntax.

Switch to the `./css/styles.css` file create some custom properties!

## Bonus

Check the stylesheet for other values that might warrant extraction. One example may be the border radius of `4px`. But you might find other things, too like letter spacing, spaces (8px, 16px, 32px), etc..

> 💡 Not everything should be a custom property. Only extract values that are **used multiple times** and that might **change together**.

> 💡 It's good practice to name your custom properties (variables) in a way that makes it clear what they are used for. For example, if you have a custom property for the border radius, you might call it `--border-radius-small`, etc..

## Notes

- You only have to touch the `./css/styles.css` file.
