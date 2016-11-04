# Project-SVG-Update

Project steps:

- Replace the background pattern PNG with the matching SVG (background.svg). Use CSS to resize the SVG to match the original design.
- Replace rasterized PNG logo with the SVG logo image of the same size (logo.svg): use the inline SVG method to add it (you'll use CSS to modify the image).
- At a page width of less than 420 pixels remove the text from the logo and add an H1 tag that contains the logo text.
- Replace dogs with SVG images of the same size using the <img> tag.
- Change icons in the menu from rasterized images to inline SVGs keeping the original image size the same.
- When a user hovers over a nav menu item, use CSS to change the color of both the text and the inline SVG.
- When submitting your project be sure to make a note in the comments which browsers and versions you have tested with.
- And remember you can only use an 'ID' once so double check the SVG images when adding them.
- Make sure to check your code is valid by running it through an HTML and CSS validator.
  - Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
  - There are a few exceptions that you don’t need to fix:
    - Don’t worry about any warnings, we just need you to check any errors that might be there.
    - If CSS validator flags use of calc, vendor prefixes or pseudo-elements/pseudo-classes these errors should be ignored.
    - If HTML validator flags use of pipe (‘|’) in Google font links/URLs this error can also be ignored.
    - The CSS Validator does not recognize the SVG attributes like fill as valid attributes. Take a look at the SVG Attribute Reference for SVG attributes that are acceptable even if they do not pass the validator.
