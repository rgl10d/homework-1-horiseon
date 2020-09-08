# Homework 1: Horiseon Homepage

In order to make the Horiseon website more accessible, to both developers and end users, and updated, rearranging and replacing HTML and CSS code was necessary.

## Div Tag Replaced

The 'div' tags were reordered and replaced with HTML semantic elements: 
  - **header** - the top-most portion of the page containing the logo and the 'nav' element
  - **nav** - contains the page navigation links
  - **figure** - holds the class that adds the background image
  - **section** - houses the core boxes of the page that describe Horiseon's abilities
  - **article** - subsets of both the 'section' and the 'aside' boxes. Refers to each individual box in the respective portions of the page. 
  - **aside** - contains the information boxes about Horiseon's benefits
  - **footer** - the bottom-most portion of the page and contains the copyright
 
This provides a more sound structure to the code so future developmental tasks are assisted with ease of navigation and identification. Each of the semantic elements listed function similarly to a 'div,' but provide a greater distinction across each of the pieces of the page when viewing the code. With the addition of the semantic elements, a reordering of the code to roughly fit the layout of the page also provides quicker and more precise navigation of the code.

## Alt Attributes
Alt attributes were added to each 'img' tag for more end user accessibility. With the alt attribute, users that are unable to view the image, because of computer, internet, or handicapped issues, can view the alt text to know what the image is of.

## CSS Consolidated
The CSS stylesheet had many redundant classes. In order to create a more clean and to-the-point stylesheet, any unnecessary class was removed and replaced with a single class that covered each element with the same styles. To assist further in the navigation of the code, new class names were added to better indicate what the styles were changing and where they were. All heading decendant elements were reordered within the stylesheet as well to easily find the necessary style changes.

## License
MIT License

Copyright © [2020] [Garrett Lee]

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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.