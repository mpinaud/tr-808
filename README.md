# Roland TR-808

#### A Web page that showcases a Roland TR-808 for sale with info, reference photos, 2017

#### by **Mikey Pinaud**

## Description

This web page provides info for a Roland TR-808 for sale. The user will have the opportunity to purchase buy either adding to a cart or buying immediately. There will be a brief product description of history plus photos of what comes with purchase with a reference photo gallery. A seller price table graph will provide price, shipping price, and return terms. A specs table graph will provide input/outputs, dimensions, net weight, power consumption, steps, memory tracks, and instruments.

## Elements Used
<table>
<!--header  -->
  <thead>
    <tr>
      <th>TERM</th>
      <th>DESCRIPTION</th>
      <th>IMPLEMENTATION</th>
    </tr>
  </thead>
<!--body  -->
  <tbody>
    <tr>
      <td>BOX-SIZING</td>
      <td>This property tells the browser what parts of the box model should be included in the elements total width and the height.</td>
      <td>In this project I've applied border-box to all the elements in the browser in order to normalize all the outside dimensions of every container. To achieve this I used the asterisk selector which applied 0 margin and 0 padding to all elements on the page.</td>
    </tr>
    <tr>
      <td>FLOAT</td>
      <td>This property takes an element out of the normal flow of it's containing element, without removing it from the flow entirely The values specify the direction the element should be moved.</td>
      <td>I've applied float to numerous elements to move them out of the way of a block while maintaining a wrap effect. For my photo gallery I used float left if keep all of my images wrapping left of each other within the photos box model. For my navigation bar I used float left for the Roland logo and float right for the shopping cart icon and menu text.</td>
    </tr>
    <tr>
      <td>DISPLAY: BLOCK</td>
      <td>An element using this property will take up the full width available in it's box model, while adding a new line before and after.</td>
      <td>I've applied display: block to my Buy It Now and Add to cart buttons so that they would stack over one another within the box. I've also added this to my description section to stack the p elements over one another.</td>
    </tr>
    <tr>
      <td>DISPLAY: INLINE</td>
      <td>An element using this property takes up only as much width as it needs, and does not force new lines.</td>
      <td>I've applied display: inline to the h1 elements in my navigation bar so they would sit within it's box model side by side</td>
    </tr>
    <tr>
      <td>CENTERED CONTENT</td>
      <td>Centering content can be done using numerous techniques given which element. This can be achieved for text using text-align: center. For a block or image this can be achieved by setting both margin left and right to auto while setting your width length</td>
      <td>I've applied this technique to my description section so that it is centered within it's box model.</td>
    </tr>
    <tr>
      <td>PSEUDO-ELEMENT</td>
      <td>A CSS pseudo-element is used to style specified parts of an element. For example, it can be used to style the first letter, or line, of an element or insert content before, or after, the content of an element.</td>
      <td>I've applied this to the first letters of each p element within the description section by changing the font color to yellow.</td>
    </tr>
    <tr>
      <td>PSEUDO-CLASS</td>
      <td>A pseudo-class is used to define a special state of an element. For example, it can be used to style an element when a user mouses over it, style visited and unvisited links differently, style an element when it gets focus</td>
      <td>For my navigation bar, Buy It Now/Add to cart buttons, and social media icons I've added a pseudo class of hover which enables an action when the mouse is hovered over that object.</td>
    </tr>
    <tr>
      <td>CLEAR-FIX</td>
      <td>The clear property lets you specify what elements can float beside the cleared element and on which side.</td>
      <td>I've applied this technique to my image gallery for each time I needed a break for all images floating left of each other. By using clear: both it enabled no floating elements allowed on either the left or the right side which pushed that row of elements down.</td>
    </tr>
    <tr>
      <td>POSITIONAL SELECTOR</td>
      <td>This property is used to select specific element(s) you want to style.</td>
      <td>I've applied this to a few elements which I needed to stylize specifically within a box model. For example, using h2:nth-child(2) to change the font size and position of my second h2 element.</td>
    </tr>
    <tr>
      <td>SELECTOR COMBINATOR</td>
      <td>A combinator is something that explains the relationship between the selectors. A selector can contain more than one simple selector. Between the simple selectors, we can include a combinator.</td>
      <td>I've used numerous descendant selectors to match all elements that are descendants of a specified element. For example I stylized my main TR-808 image by selecting the main-image parent and combining it with the img child. To do this I used .main-image img{}. </td>
    </tr>
  </tbody>
</table>

## Setup/Installation Requirements

[View on web browser](https://mpinaud.github.io/tr-808/)

Clone or download repository:
  1. Open [this page](https://github.com/mpinaud/tr-808) in web browser.
  2. Under the repository name, click Clone or download.
  3. In the Clone with HTTPs section, click to copy the clone URL for the repository.
  4. Open Terminal.
  5. Change the current working directory to the location where you want the cloned directory to be made (ex. cd desktop).
  6. Type git clone, and then paste the URL you copied in Step 3. (ex. git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY).
  7. Press Enter. Your local clone will be created.

## Technologies Used
  * HTML
  * CSS

## License

  Copyright (c) 2017 Mikey Pinaud

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
