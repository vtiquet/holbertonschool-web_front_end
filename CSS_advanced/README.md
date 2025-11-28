<div align="center"><img src="https://github.com/vtiquet/holbertonschool-resources/blob/main/image/Holberton-Logo.svg" width=40% height=40%/></div>

# Resources

## Table of Contents :

  - [0. Let's get some images!](#subparagraph0)
  - [1. Effortless transitions when scrolling](#subparagraph1)
  - [2. Do you know your color values?](#subparagraph2)
  - [3. Reuse and repeat. A programmer's life should be simple with variables](#subparagraph3)
  - [4. Variables for storing certain font types](#subparagraph4)
  - [5. Variables for the font size](#subparagraph5)
  - [6. Variables for the font-weight](#subparagraph6)
  - [7. Integrating Google Fonts into the CSS file](#subparagraph7)
  - [8. Defining line heights](#subparagraph8)
  - [9. Links are decorated by default, time to remove them](#subparagraph9)
  - [10. Centering the section titles](#subparagraph10)
  - [11. Add more styles to the section tagline](#subparagraph11)
  - [12. Adding more styling to the section title](#subparagraph12)
  - [13. Pseudo Classes](#subparagraph13)
  - [14. Resetting the CSS stylesheet for browser consistency](#subparagraph14)
  - [15. Add universal box-sizing](#subparagraph15)
  - [16. Styling the container](#subparagraph16)
  - [17. Adding padding to sections](#subparagraph17)
  - [18. Customizing the navbar](#subparagraph18)
  - [19. Grid styling and custom variables](#subparagraph19)
  - [20. Clear the context of the grid](#subparagraph20)
  - [21. Simplify the col- selector](#subparagraph21)
  - [22. Add a dark theme to sections](#subparagraph22)
  - [23. Fix issues for dark theme](#subparagraph23)
  - [24. Add background and hover state to services](#subparagraph24)
  - [25. Add border to the button](#subparagraph25)
  - [26. Add border radius to images](#subparagraph26)
  - [27. Styling the section hero](#subparagraph27)
  - [28. Fixing the header and menu navigation bar](#subparagraph28)
  - [29. Styling and custom properties for the nav](#subparagraph29)
  - [30. Fix the works section](#subparagraph30)
  - [31. Add quotes decoration on testimonials](#subparagraph31)
  - [32. Incorporating transitions](#subparagraph32)

## Resources
### Read or watch:
* [CSS Reference - A free visual guide to CSS](/rltoken/_ktDSjqTMRt3pFaxKYjpmA)
* [Can I use,,, Support tables for HTML5, CSS3, etc](/rltoken/9AX9sdvpIcezSuBnKttlrg)
* [CSS Reference](/rltoken/NuOB1JTGJe3BMvyOYXFlyw)
* [CSS Properties | HTML Dog](/rltoken/WhK8mrHj9dcxtdnNV--xFQ)
* [Box Sizing](/rltoken/f74EkDxPwhBsrHymBIiViw)
* [CSS Specificity](/rltoken/CvXsHJkf5vzSQWOZwty7Xg)
* [CSS specificity calculator](/rltoken/yyMP5u3A8BJzt2WNAngkqA)
* [Play with CSS selector](/rltoken/HhhSyJNnNQPrxzuyDSMAjA)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* Selectors, properties, and values
* The difference between block and inline styling
* How to ensure consistency across all browers (CSS reset)
* How to setup CSS variables
* The differences between inline, embeded and external CSS
* How grid systems work (with floats)
* The difference between icons webfonts and SVG icons
* The difference between pseudo-classes and pseudo-elements
* How to make background gradients
* How to animate elements in CSS
* How to transform (2d, 3d) elements
* What vendor prefixes are

## Requirements
### General
* Allowed editors:vi,vim,emacs,VSCode,Atom
* All your files will be interpreted on Chrome (version 78.x)
* All your files should end with a new line
* All your files should start by a comment describing the task
* AREADME.mdfile, at the root of the folder of the project, is mandatory
* Your code should be W3C compliant and validate withW3C-Validator

## Task
### 0. Let's get some images! <a name='subparagraph0'></a>

The description of the project contains some inspiration for the final look of the project but we’ll have to download some images.

Head to <a href="/rltoken/pyz9S8yOuFK6cwTnkXUohw" target="_blank" title="unsplash">unsplash</a> and download 10 high resolution images that look as close to the final product that you’re going to make. You will be using these same high res images for a project on <code>Responsive Design</code> in the future. Remember to also include the 3 images (the 2 logos and the favicon) linked in the description of the project.

The images should all be representative of category they belong to. Images in the <code>work</code> category should be closely related to <code>work</code>.

---

### 1. Effortless transitions when scrolling <a name='subparagraph1'></a>

When scrolling is triggered on the <code>html</code> element itself, we’d like the behavior of the scroll to be as fluid as possible.

---

### 2. Do you know your color values? <a name='subparagraph2'></a>

Based on <code>styles/1-style.css</code>, create the following declarations:

* For the <code>body</code>, set the foreground color value to <code>#161616</code>
* For all anchor elements, set the foreground color value to <code>#161616</code>
* All elements with the class <code>visually-hidden</code> should have their display to <code>none</code>
* All elements with the class <code>card-category</code>, should have their foreground color set to <code>#D73953</code>
* All elements with the class <code>section-tagline</code> should have their foreground color set to <code>#D73953</code>

---

### 3. Reuse and repeat. A programmer's life should be simple with variables <a name='subparagraph3'></a>

Based on <code>styles/2-style.css</code>:

* Target the <code>root</code> element and define the following custom properties:


  * <code>color-primary</code> set to <code>#d73953</code>
  * <code>color-black</code> set to <code>#090909</code>
  * <code>color-white</code> set to <code>#ffffff</code>
  * <code>color-light-grey</code> set to <code>#f3f3f3</code>
  * <code>color-dark-grey</code> set to <code>#353535</code>
  * <code>text-color</code> set to <code>color-black</code>
* Revisit the <code>section-tagline</code> and <code>card-category</code> declarations and reset their color to <code>color-primary</code>
* Revisit the <code>body</code> and anchor declarations and reset their color to <code>text-color</code>

<strong>Does not have to pass w3c</strong>

---

### 4. Variables for storing certain font types <a name='subparagraph4'></a>

Based on <code>styles/3-style.css</code>:

* Targeting the <code>root</code> element, create 2 custom font-family properties <code>font-family-base</code> and <code>font-family-title</code> with the same list of fonts:


  * set the first choice font as <code>Helvetica Neue</code>
  * set the second choice font as <code>Helvetica</code>
  * set the third choice font as <code>Arial</code>
  * set the last choice font as <code>sans-serif</code>
* Set <code>body</code>‘s font-family to <code>font-family-base</code>
* Create a new declaration targeting all 6 levels of heading tags


  * set its font-family to <code>font-family-title</code>

<strong>Does not need to pass W3C</strong>

---

### 5. Variables for the font size <a name='subparagraph5'></a>

Based on <code>styles/4-style.css</code>:

* Targeting the <code>root</code> selector, create the following custom properties:


  * <code>font-size-small</code> set to <code>1.2rem</code>
  * <code>font-size-medium</code> set to <code>1.6rem</code>
  * <code>font-size-large</code> set to <code>1.8rem</code>
  * <code>font-size-x-large</code> set to <code>2.3rem</code>
  * <code>font-size-xx-large</code> set to <code>4.8rem</code>
* All fonts in the <code>html</code> element should be at <code>62.5%</code> of their normal size
* Any fonts in the <code>body</code> should have their sizes set to <code>font-size-medium</code>

<strong>Does not need to pass W3C</strong>

---

### 6. Variables for the font-weight <a name='subparagraph6'></a>

Based on <code>styles/5-style.css</code>

* Targeting the <code>root</code> element, create the following custom properties:


  * <code>font-weight-regular</code> set to <code>400</code>
  * <code>font-weight-bold</code> set to <code>700</code>
* Set the boldness of fonts in the <code>body</code> to <code>font-weight-regular</code>
* Set the boldness of fonts in the headings to <code>font-weight-bold</code>

<strong>Does not need to pass W3C</strong>

---

### 7. Integrating Google Fonts into the CSS file <a name='subparagraph7'></a>

Based on <code>styles/6-style.css</code>:

* Add <code>Open Sans</code> as the first choice font for <code>font-family-base</code>, with the previous fonts shifted down accordingly
* Add <code>Raleway</code> as the first choice font for <code>font-family-title</code>, with the previous fonts shifted down accordingly

<strong>Does not need to pass w3c</strong>

---

### 8. Defining line heights <a name='subparagraph8'></a>

Based on <code>styles/7-style.css</code>:

* Targeting <code>root</code>, create the following custom properties:


  * <code>line-height-small</code> set to <code>1.2</code>
  * <code>line-height-base</code> set to <code>1.5</code>
  * <code>line-height-big</code> set to <code>1.8</code>
* Set the minimum height of line boxes in the <code>body</code> to <code>line-height-base</code>

<strong>Does not need to pass w3c</strong>

---

### 9. Links are decorated by default, time to remove them <a name='subparagraph9'></a>

Based on <code>styles/8-style.css</code>

Style the anchor elements so the text isn’t decorated with anything

<strong>Does not need to pass w3c</strong>

---

### 10. Centering the section titles <a name='subparagraph10'></a>

Based on <code>styles/9-style.css</code>:

* Create a new custom property <code>section-header-align</code> and set it to <code>center</code>
* Just above the <code>section-tagline</code> declaration, create a new declaration targeting the class <code>section-header</code>

  * Set horizontal alignment of that class with <code>section-header-align</code>

<strong>Does not need to pass w3c</strong>

---

### 11. Add more styles to the section tagline <a name='subparagraph11'></a>

Based on <code>styles/10-style.css</code>:

* Create a custom property <code>section-tagline-transform</code> and set it to <code>uppercase</code>
* Targeting the <code>section-tagline</code> class:


  * Set the family of fonts to <code>font-family-title</code>
  * By using the property <code>section-tagline-transform</code>, transform the text
  * Set the weight of fonts to <code>font-weight-bold</code>

<strong>Does not need to pass w3c</strong>

---

### 12. Adding more styling to the section title <a name='subparagraph12'></a>

Based on <code>styles/11-style.css</code>:

* Create the following custom properties:


  * <code>section-title-margin</code> set to <code>0</code>
  * <code>section-title-color</code> set to <code>color-black</code>

Just above the <code>section-tagline</code> declaration, create a new declaration targeting the <code>section-title</code> class

* Set the family of fonts to <code>font-family-title</code>
* Set the font size to <code>font-size-xx-large</code>
* Set the font weight to <code>font-weight-bold</code>
* Use the <code>section-title-margin</code> to set the margin
* Use the <code>section-title-color</code> to set the text color

---

### 13. Pseudo Classes <a name='subparagraph13'></a>

Based on <code>styles/12-style.css</code>:

* Ensure that the declaration targeting anchor elements only targets those containing a hyperlink
* Directly after this declaration, target the visited state for the link


  * Italicize the text
* Directly after the visited state, target the hover state for the link


  * Decorate the links with an underline when hovering
* Directly after the hover state, target the active state for the link


  * Set the color of the background with the variable <code>color-light-grey</code>

<strong>Does not need to pass w3c</strong>

---

### 14. Resetting the CSS stylesheet for browser consistency <a name='subparagraph14'></a>

Based on <code>styles/13-style.css</code>:

Normalize your CSS file using <a href="/rltoken/0UITCJASLDBEvDQdP_pwiw" target="_blank" title="necolas' normalize.css">necolas’ normalize.css</a> with <a href="/rltoken/SE65V_9HBDJxYAuoJfK2YQ" target="_blank" title="this version">this version</a>.

<strong>Does not need to pass w3c</strong>

---

### 15. Add universal box-sizing <a name='subparagraph15'></a>

Based on <code>styles/14-style.css</code>:

Just before the styling for <code>html</code>, add a universal box sizing rule

<strong>Does not need to pass w3c</strong>

---

### 16. Styling the container <a name='subparagraph16'></a>

Based on <code>styles/15-style.css</code>:

After the styles for <code>.section-tagline</code>,

Target the <code>container</code> class and set the following:

* <code>960px</code> wide
* evenly distribute the margins on both the left and and right side

<strong>Does not need to pass w3c</strong>

---

### 17. Adding padding to sections <a name='subparagraph17'></a>

Based on <code>styles/16-style.css</code>:

* Create the following custom properties:


  * <code>section-padding</code> set to <code>5rem 0</code>
  * <code>section-header-padding</code> set to <code>0 0 3rem</code>
  * <code>section-body-padding</code> set to <code>0 0 3rem</code>
  * <code>section-footer-padding</code> set to <code>3rem 0 0</code>
  * <code>section-footer-align</code> set to <code>center</code>
  * <code>footer-padding</code> set to <code>5rem 0 1rem</code>
* Just before the <code>section-header</code> declaration, target the class <code>section</code> and set the padding on all 4 sides to <code>section-padding</code>
* Set <code>.section-header</code>‘s pad all 4 sides with <code>section-header-padding</code>
* Following the <code>section-header</code> declaration, target the <code>section-body</code> class, pad all 4 sides with <code>section-body-padding</code>
* Following the <code>section-body</code> declaration, target the <code>section-footer</code> class, pad all 4 sides with <code>section-footer-padding</code> and set the horizontal alignment with <code>section-footer-align</code>
* At the end of your style file, target the class <code>footer</code>, pad all 4 sides of the selected element with <code>footer-padding</code>

<strong>Does not need to pass w3c</strong>

---

### 18. Customizing the navbar <a name='subparagraph18'></a>

Based on <code>styles/17-style.css</code>:

* Targeting the <code>navbar-menu</code> class, let it float to the right
* For the <code>nav</code> class:


  * the margin on all sides should be set to <code>0</code>
  * the padding on all sides should be set to <code>0</code>
  * The styling on the list should not use anything
  * center align the text
* For the <code>nav-item</code> class in <code>nav</code> class:


  * set the family of fonts to <code>nav-item-font-family</code>
  * set the boldness of fonts to <code>nav-item-font-weight</code>
  * set the size of fonts to <code>nav-item-font-size</code>
  * set the spacing between text characters to <code>nav-item-letter-spacing</code>
  * set the display to <code>nav-item-display</code>
  * set the margin on all sides to <code>nav-item-margin</code>
* For the <code>nav-link</code> class in <code>nav</code> class:


  * set the display to <code>block</code>
  * set the padding to half of the root element for top and bottom, and equal to the root element for left and right
* While hovering over the <code>nav-link</code> class in <code>nav</code> class, set their foreground color value to <code>nav-item-link-hover</code>
* Create the following custom properties:


  * <code>nav-item-font-family</code> set to <code>font-family-title</code>
  * <code>nav-item-font-weight</code> set to <code>font-weight-bold</code>
  * <code>nav-item-font-size</code> set to<code>font-size-medium</code>
  * <code>nav-item-letter-spacing</code> set to 4% of the root element
  * <code>nav-item-display</code> to <code>inline-block</code>
  * <code>nav-item-margin</code>to 3 times the root element on the bottom and <code>0</code> elsewhere
  * <code>nav-item-link-hover</code> set to <code>color-primary</code>

<strong>Does not need to pass w3c</strong>

---

### 19. Grid styling and custom variables <a name='subparagraph19'></a>

Based on <code>styles/18-style.css</code>:

* Create the custom property <code>section-tagline-margin</code> set to <code>0</code>
* Set the margins for the <code>section-tagline</code> class to <code>section-tagline-margin</code>
* For all <code>ul</code> with the class <code>row</code>:


  * 0 margins all around
  * No padding all around
  * the list should not have any default styles at all
* For the <code>col-1-3</code> class:


  * set the width to 33.33% of its parent
  * float it to the left
  * set its padding to half of the root element
* For the <code>col-1-2</code> class:


  * set the width to 50% of the parent
  * float it to the left
  * set its padding to half of the root element
* For the <code>footer-copyright</code> class:


  * No margins
  * Set the size of the fonts to <code>font-size-small</code>
  * set the foreground color to <code>text-color</code>
* For all <code>ul</code>  tag in the <code>footer</code> class, align the text to the right

<strong>Does not need to pass w3c</strong>

---

### 20. Clear the context of the grid <a name='subparagraph20'></a>

Based on <code>styles/19-style.css</code>:

Write a CSS rule that creates a new row after each instance of the class <code>row</code> with the following properties:

* no content
* displayed as a table
* do not allow any floating elements on either side

<strong>Does not have to pass w3c</strong>

---

### 21. Simplify the col- selector <a name='subparagraph21'></a>

Based on <code>styles/20-style.css</code>:

* Select all classes that start with <code>col-</code>

  * float them to the left
  * set their padding to half of the root element
  * <em>Hint: be mindful of specificity</em>
* Remove references to these common properties for the individual <code>col-1-3</code> and <code>col-1-2</code> classes

<strong>Does not need w3c</strong>

---

### 22. Add a dark theme to sections <a name='subparagraph22'></a>

Based on <code>styles/21-style.css</code>:

Style the data-section-theme=“dark” with these rules:

* Redefine the custom property <code>text-color</code> to the <code>color-white</code>
* Redefine the custom property <code>section-title-color</code> to <code>color-white</code>
* Set the background to the variable <code>color-black</code>

<strong>Does not need to pass w3c</strong>

---

### 23. Fix issues for dark theme <a name='subparagraph23'></a>

Based on <code>styles/22-style.css</code>:

Style the <code>footer-address</code> class

* Set the color of the text to the <code>text-color</code> property

Style the <code>social-link</code> class:

* Style it so that it renders as a block element

Style the <code>social-link</code> class that also selects the <code>svg</code> children

* Fill in the color of the svg children with the <code>text-color</code> variable

<strong>Does not have to pass w3c</strong>

---

### 24. Add background and hover state to services <a name='subparagraph24'></a>

Based on <code>styles/23-style.css</code>

Target <code>card-title</code> that is inside <code>card-services</code>

* The margin on all sides should be none at all

Target <code>a</code> that is inside <code>card-services</code>

* Have them render as block level elements
* The padding should be set to 2x the root element
* Set the background color to the variable <code>color-light-grey</code>

Target the hover state of <code>a</code> that is inside <code>card-services</code>

* Set the foreground color to the variable <code>color-white</code>
* Set the color of the background to the variable <code>color-primary</code>
* Text should not be decorated at all

<strong>Does not need to pass w3c</strong>

---

### 25. Add border to the button <a name='subparagraph25'></a>

Based on <code>styles/24-style.css</code>

Add custom properties to the root selector in the css file

* Name: <code>button-display</code>, Value: <code>inline-block</code>
* Name: <code>button-padding</code>, Value: <code>1.5rem 3rem</code>
* Name: <code>button-border</code>, Value: <code>0.2rem solid var(--color-primary)</code>
* Name: <code>button-color</code>, Value: <code>color-black</code>
* Name: <code>button-text-decoration</code>, Value: <code>none</code>
* Name: <code>button-font-size</code>, Value: <code>font-size-large</code>
* Name: <code>button-hover-color</code>, Value: <code>color-white</code>
* Name: <code>button-hover-text-decoration</code>, Value: <code>none</code>
* Name: <code>button-hover-background</code>, Value: <code>color-primary</code>

Add these selectors after the selector for anchor links in active state:

* <p>Create the button class selector</p>

  * Set the display of the button to the variable <code>button-display</code>
  * Add padding all around with the variable <code>button-padding</code>
  * Style the border with the variable <code>button-border</code>
  * Set the size of fonts to the variable <code>button-font-size</code>
  * Set the foreground color to the variable <code>button-color</code>
  * Decorated text should have the value of the variable <code>button-text-decoration</code>
* <p>Create the hover state of the button class selector</p>

  * Set the foreground color value to the variable <code>button-hover-color</code>
  * Decorated text should have the value of the variable <code>button-hover-text-decoration</code>
  * Use the value of the variable <code>button-hover-background</code> for the background
* <p>In <code>[data-section-theme="dark"]</code>, add the variable</p>

  * Create a custom property <code>button-color</code> pointing to the variable <code>color-white</code>

<strong>Does not have to pass w3c</strong>

---

### 26. Add border radius to images <a name='subparagraph26'></a>

Based on <code>styles/25-style.css</code>

Add the <code>card-testimonial</code> selector

* Center align the text

Target the <code>card-avatar</code> that is inside the <code>card-testimonial</code>

* Round the radius on all sides at 50%
* Set the width to 10x the root element
* Set the height to 10x the root element

Target the <code>&lt;cite&gt;</code> HTML tag which is inside <code>card-quote</code> inside the <code>card-testimonial</code>

* Style as a block level element
* Pad the top with 1x the root element
* Set the foreground color value to the value of the color-primary variable

<strong>Does not have to pass w3c</strong>

---

### 27. Styling the section hero <a name='subparagraph27'></a>

Based on <code>styles/26-style.css</code>

Add the <code>section-hero</code> selector

* Set the size of the background using 2-value syntax
* Width should be <code>90rem</code> and the height should be set automatic

Target the <code>section-title</code> inside the <code>section-hero</code>

* Add 5rem of margin to the bottom

Target the <code>section-inner</code> inside the <code>section-hero</code>

* Add 10rem, 40rem, 2rem, and 0 to the padding on the top, right, bottom, left all in 1 rule

<strong>Does not have to pass w3c</strong>

---

### 28. Fixing the header and menu navigation bar <a name='subparagraph28'></a>

Based on <code>styles/27-style.css</code>

Create these custom properties

* Name: <code>header-padding</code>, Value: <code>4rem 0 0</code>
* Name: <code>header-logo-position</code>, Value: <code>relative</code>
* Name: <code>header-logo-link-display</code>, Value: <code>inline-block</code>
* Name: <code>header-logo-link-position</code>, Value: <code>absolute</code>
* Name: <code>header-logo-link-top</code>, Value: <code>-1rem</code>
* Name: <code>header-logo-link-left</code>, Value: <code>0</code>

Create a header class selector

* Pad the header with the value within the variable <code>header-padding</code>

Create a <code>header-logo</code> class selector

* Position the <code>header-logo</code> with the value of the variable <code>header-logo-position</code>

Target the link inside the <code>header-logo</code> class

* Render the display using the value of the variable <code>header-logo-link-display</code>
* Position the links with the value of the variable <code>header-logo-link-position</code>
* Set the vertical position of the element using <code>header-logo-link-top</code>
* Set the horizontal position of the element using <code>header-logo-link-left</code>

<strong>Does not have to pass w3c</strong>

---

### 29. Styling and custom properties for the nav <a name='subparagraph29'></a>

Based on <code>styles/28-style.css</code>

Edit the <code>nav-item-link-hover</code> property by setting its value to the <code>color-white</code>variable

Target the before pseudo elements of <code>nav-link</code> that is inside the <code>nav</code>

* Set the values of these elements to <code>empty</code> using <code>content</code>
* Absolutely position the targeted elements
* Set the vertical position to 0
* The horizontal position of the targeted elements should be 0
* Set the color of the background color of the targeted elements to the value <code>color-white</code>
* The width of the targeted elements should be set to 0
* Set the height to 20% of the root element value

Target the before pseudo elements of <code>nav-link</code> when <code>nav-item</code> is hover and is inside <code>nav</code>

* Set the background color of the elements to the variable <code>color-primary</code>
* Set the width of the elements to <code>100%</code>

<strong>Does not have to pass w3c</strong>

---

### 30. Fix the works section <a name='subparagraph30'></a>

Based on <code>styles/29-style.css</code>

Target <code>card-outer</code> within the <code>card-work</code>

* Relatively position the element
* Hide any overflow

Target the image inside <code>card-image</code> inside <code>card-work</code>

* The height of these elements should be <code>30rem</code>
* The width of this element should be 100%
* Property: <code>object-fit</code>, Value: <code>cover</code>
* Vertically align to the bottom

Target <code>card-inner</code> inside <code>card-work</code>

* Absolutely position the element
* Vertically position with <code>-0.1rem</code> on the top
* Horizontally position the element with <code>-0.1rem</code> on the left
* Horizontally position the element with <code>-0.1rem</code> on the right
* Set the <code>z-index</code> to <code>1</code>

Target <code>card-inner</code> when card-work is <code>hover</code>

* Set the background color to this value: <code>rgba(0, 0, 0, 0.7)</code>

Target <code>card-title</code> inside <code>card-work</code>

* Center align the text
* Margins all around should be <code>0</code>
* Opacity should be set to its lowest value
* The height of the selected elements should be <code>100%</code>
* The position should be relative

Target the link inside <code>card-title</code> and <code>card-work</code>

* Make sure elements display as blocks
* Text should not be decorated
* Padding on the top should be <code>45%</code>

Create the after pseudo elements of the link (inside <code>card-title</code> and <code>card-work</code>)

* Absolutely position the selected elements
* Set the top, right, left, and bottom positions to be 0
* The content property of these elements should have an empty value

Target <code>card-title</code> when <code>card-work</code> is hover

* The opacity of these elements should be set to the value of <code>1</code>

<strong>Does not have to pass w3c</strong>

---

### 31. Add quotes decoration on testimonials <a name='subparagraph31'></a>

Target the card-quote that is inside the card-testimonial

* Style it so that the position is relative to its parent

Target the before pseudo-element of card-quote that is inside the card-testimonial

* The content should be set to the value <code>\201C</code>
* Absolutely position the selected elements
* The vertical position of the selected elements should be <code>-4.5rem</code>
* The horizontal position from the left should be <code>-1rem</code>
* The foreground color of the selected elements should be set to <code>#efeded</code>
* The size of fonts should be <code>10rem</code>
* The <code>z-index</code> should be set to <code>-1</code>

<strong>Does not have to pass w3c</strong>

---

### 32. Incorporating transitions <a name='subparagraph32'></a>

<strong>Create some custom properties</strong>

* Name: <code>transition-duration</code>, Value: <code>.3s</code>
* Name: <code>transition-cubic-bezier</code>, Value: <code>cubic-bezier(0.17, 0.67, 0, 1.01)</code>

<strong>Add transformations on the card work</strong>

Target the card-image when card-work is hover

* Use the transform property to apply a scale transform with a value of  <code>scale(1.2)</code>

Target the card-outer when card-work is hover

* Use the transform property apply a scale transform to make the elements shrink. Use  <code>scale(0.95)</code>

<strong>Add animations on the navigation items</strong>

Inside <code>.nav .nav-link::before</code>

* Use the shorthand property <code>transition</code> and have it use the value of <code>var(--transition-duration) var(--transition-cubic-bezier)</code>

<strong>Animate the button background</strong>

In the hover state of the button class

* The duration of the transition should be set to the variable <code>transition-duration</code>
* The transition effect should be applied to the <code>color</code> and <code>background-color</code> properties (<code>transition-property</code>)

<strong>Add transitions on the card works</strong>

Inside <code>card-work:hover .card-image</code>

* Use the shorthand property <code>transition</code> and have it use the value of <code>var(--transition-duration) var(--transition-cubic-bezier)</code>

Inside <code>.card-work .card-inner</code>

* Use the shorthand property <code>transition</code> and have it use the value of <code>var(--transition-duration) var(--transition-cubic-bezier)</code>

<strong>Does not have to pass w3c</strong>

---


## Authors
vtiquet - [GitHub Profile](https://github.com/vtiquet)
