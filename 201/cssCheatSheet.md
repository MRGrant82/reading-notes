# **color**

Examples:
- color: red;: Sets the text color to red.
- color: #00ff00;: Sets the text color to lime green using a hexadecimal value.
- color: rgb(255, 165, 0);: Sets the text color to orange using an RGB value.
- color: hsl(0, 100%, 50%);: Sets the text color to red using an HSL value.
- color: rgba(0, 0, 255, 0.5);: Sets the text color to translucent blue using an RGBA value.

Explanation: The color function is used to specify the color of the text in an element. This can be useful for making text stand out or to match the color scheme of a website.

# **background-color**

Examples:
- background-color: #000000;: Sets the background color to black using a hexadecimal value.
- background-color: rgb(255, 255, 0);: Sets the background color to yellow using an RGB value.
- background-color: hsl(120, 100%, 50%);: Sets the background color to lime green using an HSL value.
- background-color: transparent;: Makes the background color transparent, allowing any underlying content to show through.
- background-color: inherit;: Inherits the background color from the parent element.

Explanation: The background-color function is used to set the background color of an element. This can be useful for adding visual interest to a page or to provide visual cues to the user.

# **font-size**

Examples:
- font-size: 12px;: Sets the font size to 12 pixels.
- font-size: 1.5em;: Sets the font size to 1.5 times the current element's font size.
- font-size: medium;: Sets the font size to the medium size as defined by the user's browser preferences.
- font-size: smaller;: Sets the font size to a smaller size than the parent element.
- font-size: larger;: Sets the font size to a larger size than the parent element.

Explanation: The font-size function is used to set the size of the font used for text in an element. This can be useful for adjusting the readability or visual appearance of the text.

# **font-family**

Examples:
- font-family: Arial, sans-serif;: Sets the font family to Arial or a sans-serif font if Arial is not available.
- font-family: Georgia, serif;: Sets the font family to Georgia or a serif font if Georgia is not available.
- font-family: "Comic Sans MS", cursive;: Sets the font family to Comic Sans MS or a cursive font if Comic Sans MS is not available.
- font-family: "Helvetica Neue", Helvetica, sans-serif;: Sets the font family to Helvetica Neue or Helvetica or a sans-serif font if neither is available.
f- ont-family: inherit;: Inherits the font family from the parent element.

Explanation: The font-family function is used to specify the font family used for text in an element. This can be useful for matching the font style to the tone of the website or for consistency across different pages.

# **text-align**

Examples:
text-align: left;: Aligns the text to the left of the element.
- text-align: right;: Aligns the text to the right of the element.
- text-align: center;: Centers the text within the element.
- text-align: justify;: Justifies the text within the element, causing the spaces between words to stretch to fill the available space.
- text-align: inherit;: Inherits the text alignment from the parent element.

Explanation: The text-align function is used to set the horizontal alignment of text within an element. This can be useful for improving the readability or visual appearance of the text.

# **border**

Examples:
- border: 1px solid black;: Sets a solid black border with a width of 1 pixel.
- border: 2px dashed red;: Sets a dashed red border with a width of 2 pixels.
- border-top: 3px dotted blue;: Sets a dotted blue border on the top side of the element with a width of 3 pixels.
- border-radius: 10px;: Sets a border radius of 10 pixels, rounding the corners of the element.
- border-image: url(border.png) 27 27 round;: Sets a border image for the element with a 27 pixel offset and a round repeat pattern.

Explanation: The border function is used to add a border around an element. The border can be customized with various properties such as style, width, and color.

# **padding**

Examples:

- padding: 10px;: Adds 10 pixels of padding to all sides of the element.
- padding-top: 5px;: Adds 5 pixels of padding to the top side of the element.
- padding-left: 20px;: Adds 20 pixels of padding to the left side of the element.
- padding: 5px 10px;: Adds 5 pixels of padding to the top and bottom sides of the element and 10 pixels of padding to the left and right sides of the element.
- padding: 0;: Removes all padding from the element.

Explanation: The padding function is used to add padding (or space) inside an element between its content and its border. This can be useful for creating visual separation between elements or for adjusting the layout of a page.

# **margin**

Examples:

- margin: 10px;: Adds 10 pixels of margin to all sides of the element.
- margin-top: 5px;: Adds 5 pixels of margin to the top side of the element.
- margin-left: 20px;: Adds 20 pixels of margin to the left side of the element.
- margin: 5px 10px;: Adds 5 pixels of margin to the top and bottom sides of the element and 10 pixels of margin to the left and right sides of the element.
- margin: 0;: Removes all margin from the element.

Explanation: The margin function is used to add margin (or space) outside an element between it and other elements. This can be useful for adjusting the layout of a page or for creating visual separation between elements.

# **display**

Examples:

- display: block;: Displays the element as a block-level element, taking up the full width of its parent element.
- display: inline;: Displays the element as an inline-level element, allowing other elements to appear on the same line.
- display: none;: Hides the element completely.
- display: flex;: Displays the element as a flex container, allowing flexible positioning and sizing of its child elements.
- display: table;: Displays the element as a table, allowing table-like formatting of its child elements.

Explanation: The display function is used to control how an element is displayed on the page. This can be useful for adjusting the layout of a page or for displaying certain elements in a specific way.

# **position**

Examples:

- position: static;: The default position value; the element is positioned according to its place in the normal flow of the document. 
- position: relative;: Positions the element relative to its normal position in the document flow. 
- position: absolute;: Positions the element relative to its nearest positioned ancestor (i.e., an ancestor with a position value of anything other than static). 
- position: fixed;: Positions the element relative to the viewport, so it stays in the same place even if the page is scrolled. 
- position: sticky;`: Positions the element as if it were relatively positioned until it reaches a certain point on the page, after which it becomes fixed in place.

Explanation: The position function is used to set the position of an element on the page. This can be useful for creating specific layouts or for positioning certain elements in a specific way.

# **float**

Examples:

- float: left;: Floats the element to the left of its parent element.
- float: right;: Floats the element to the right of its parent element.
- float: none;: The default value; the element is not floated.
- float: inherit;: Inherits the float value from its parent element.
clear: both;: Clears any floats on both the left and right sides of the element.

Explanation: The float function is used to float an element to the left or right of its parent element. This can be useful for creating layouts with text wrapping around images or other elements.

# **width**

Examples:

- width: 100%;: Sets the width of the element to 100% of its parent element's width.
- width: 200px;: Sets the width of the element to 200 pixels.
width: auto;: Sets the width of the element to its default width (i.e., the width of its content).
- max-width: 500px;: Sets the maximum width of the element to 500 pixels.
- min-width: 100px;: Sets the minimum width of the element to 100 pixels.

Explanation: The width function is used to set the width of an element on the page. This can be useful for creating specific layouts or for ensuring that certain elements are a certain size.

# **height**

Examples:

- height: 100%;: Sets the height of the element to 100% of its parent element's height.
- height: 200px;: Sets the height of the element to 200 pixels.
- height: auto;: Sets the height of the element to its default height (i.e., the height of its content).
- max-height: 500px;: Sets the maximum height of the element to 500 pixels.
- min-height: 100px;: Sets the minimum height of the element to 100 pixels.

Explanation: The height function is used to set the height of an element on the page. This can be useful for creating specific layouts or for ensuring that certain elements are a certain size.

# **overflow**

Examples:

- overflow: auto;: Adds a scroll bar to the element if its content overflows its boundaries.
- overflow: hidden;: Hides any content that overflows the element's boundaries.
- overflow: visible;: Displays any content that overflows the element's boundaries (this is the default value).
- overflow-x: scroll;: Adds a horizontal scroll bar to the element if its content overflows its boundaries.
- overflow-y: hidden;: Hides any vertical content that overflows the element's boundaries.

Explanation: The overflow function is used to control what happens when content overflows an element's boundaries. This can be useful for controlling the layout and appearance of a page.

# **text-decoration**

Examples:
- text-decoration: underline;: Underlines the text in the element.
- text-decoration: line-through;: Draws a line through the text in the element.
- text-decoration: none;: Removes any text decoration from the element (this is the default value).
- text-decoration: overline;: Draws a line over the text in the element.
- text-decoration: blink;: Makes the text blink on and off (this is not widely supported and is generally not recommended for use).

Explanation: The text-decoration function is used to add various decorations to the text in an element. This can be useful for drawing attention to certain text or for indicating that certain text is important.

# **text-transform**

Examples:

- text-transform: uppercase;: Converts all text in the element to uppercase.
- text-transform: lowercase;: Converts all text in the element to lowercase.
- text-transform: capitalize;: Capitalizes the first letter of each word in the element.
- text-transform: none;: Does not apply any text transformation (this is the default value).
- text-transform: inherit;: Inherits the text transformation from its parent element.

Explanation: The text-transform function is used to transform the case of the text in an element. This can be useful for ensuring consistency in the case of text or for emphasizing certain words.

# **text-shadow**

Examples:

- text-shadow: 1px 1px black;: Adds a black drop shadow to the text with an offset of 1 pixel to the right and 1 pixel down.
- text-shadow: -1px -1px white;: Adds a white drop shadow to the text with an offset of 1 pixel to the left and 1 pixel up.
- text-shadow: 0 0 5px blue;: Adds a blue glow to the text with a radius of 5 pixels.
- text-shadow: none;: Removes any text shadow from the element (this is the default value).
- text-shadow: inherit;: Inherits the text shadow from its parent element.

Explanation: The text-shadow function is used to add a shadow or glow effect to the text in an element. This can be useful for emphasizing certain text or for adding visual interest to a page.

# **box-shadow**

Examples:

- box-shadow: 5px 5px 10px black;: Adds a black drop shadow to the element with an offset of 5 pixels to the right and 5 pixels down and a blur radius of 10 pixels.
- box-shadow: -5px -5px 10px white;: Adds a white drop shadow to the element with an offset of 5 pixels to the left and 5 pixels up and a blur radius of 10 pixels.
- box-shadow: 0 0 5px blue;: Adds a blue glow to the element with a radius of 5 pixels.
- box-shadow: none;: Removes any box shadow from the element (this is the default value).
- box-shadow: inherit;: Inherits the box shadow from its parent element.

Explanation: The box-shadow function is used to add a shadow or glow effect to an element. This can be useful for emphasizing certain elements or for adding visual interest to a page.

# **opacity**

Examples:

- opacity: 1;: Sets the opacity of the element to 100% (this is the default value).
- opacity: 0.5;: Sets the opacity of the element to 50%.
- opacity: 0;: Sets the opacity of the element to 0, making it completely transparent.
- opacity: inherit;: Inherits the opacity from its parent element.
visibility: hidden;: Hides the element completely without affecting the layout of the page.

Explanation: The opacity function is used to set the opacity (or transparency) of an element. This can be useful for creating visual effects or for hiding elements without affecting the layout of the page.

- text-align-last

Examples:

- text-align-last: auto ;: Aligns the last line of the text according to the value of the text-alignproperty (this is the default value). 

- text-align-last: left;: Aligns the last line of the text to the left of the element. 
- text-align-last: right;: Aligns the last line of the text to the right of the element. 
- text-align-last: center;: Centers the last line of the text within the element. 
- text-align-last: justify;`: Justifies the last line of the text within the element, causing the spaces between words to stretch to fill the available space.

Explanation: The text-align-last function is used to set the horizontal alignment of the last line of text within an element. This can be useful for improving the appearance of the text and making it more readable.

# **background-color **

Examples:

- background-color: white;: Sets the background color of the element to white (this is the default value).
- background-color: #FF0000;: Sets the background color of the element to red.
- background-color: rgb(0, 255, 0);: Sets the background color of the element to green.
- background-color: rgba(255, 255, 0, 0.5);: Sets the background color of the element to yellow with an opacity of 50%.
- background-color: transparent;: Makes the background of the element transparent.

Explanation: The background-color function is used to set the background color of an element. This can be useful for adding color and visual interest to a page.

# **background-image**

Examples:

- background-image: url("background.png");: Sets the background image of the element to an image file called "background.png".
- background-image: linear-gradient(red, yellow);: Creates a linear gradient background that fades from red to yellow.
- background-image: radial-gradient(circle at 50% 50%, blue, white);: Creates a radial gradient background that fades from blue to white.
- background-image: none;: Removes any background image from the element (this is the default value).
- background-image: inherit;: Inherits the background image from its parent element.

Explanation: The background-image function is used to set the background image of an element. This can be useful for adding visual interest and texture to a page.

# **background-repeat**

Examples:

- background-repeat: repeat;: Tiles the background image horizontally and vertically to fill the entire element (this is the default value).
- background-repeat: repeat-x;: Tiles the background image horizontally to fill the entire element.
- background-repeat: repeat-y;: Tiles the background image vertically to fill the entire element.
- background-repeat: no-repeat;: Displays the background image only once, without tiling.
- background-repeat: space;: Tiles the background image evenly to fill the entire element, with any leftover space evenly distributed between the tiles.

Explanation: The background-repeat function is used to control how a background image is repeated within an element. This can be useful for creating specific patterns or visual effects.

# **background-position**

Examples:

- background-position: left top;: Positions the background image at the top left corner of the element (this is the default value).
- background-position: center center;: Positions the background image at the center of the element.
- background-position: right bottom;: Positions the background image at the bottom right corner of the element.
- background-position: 50% 25%;: Positions the background image so that its center is at 50% of the element's width and its top edge is at 25% of the element's height.
- background-position: inherit;: Inherits the background position from its parent element.

Explanation: The background-position function is used to set the position of a background image within an element. This can be useful for adjusting the placement of the image or for creating specific visual effects.

# **background-size**

Examples:
- background-size: auto;: Displays the background image at its default size (this is the default value).
- background-size: cover;: Scales the background image to cover the entire element, while maintaining its aspect ratio.
- background-size: contain;: Scales the background image to fit within the element, while maintaining its aspect ratio.
- background-size: 50% auto;: Scales the background image to be 50% of the element's width and to maintain its original height.
- background-size: inherit;: Inherits the background size from its parent element.

Explanation: The background-size function is used to control the size of a background image within an element. This can be useful for adjusting the size of the image or for creating specific visual effects.
