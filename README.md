# Code-Refactor-Homework-01


- This project was a refactoring of a marketing agencies webpage to clean up the code and
  apply semantic standards to the HTML tags.

- link to project: https://bob-w-perez.github.io/Code-Refactor-Homework-01/


-- Changes made to index.html

----- replaced generic 'div' tags with more descriptive alternatives such as 'main', 'aside',
      'nav', 'header', etc.

----- by giving these elements distinct tags, many of their classes were made irrelevant and
      were therefore removed

----- a broken link in the navbar was fixed by adding an 'id' attribute to its target element

----- 'alt' attributes were added to all of the pages images, except for the hero image which
      was tagged as a figure to preserve its corresponding CSS declaration

----- unnecessary 'class' attributes were removed from the images, these classes only refered
      to single elements and were redundant for the webpage's functionality

----- a descriptive title and heart-shaped favicon were added to the browser tab

----- the 'seo' in the Horiseon page heading were a different color to highlight the S.E.O
      aspects of the company, but the difference was barely noticeable so the color was changed
      to highlight it better


-- Changes made to style.css

----- class selectors that were no longer necessary due to the new element tags in the HTML
      were replaced by the corresponding element selector

----- some declarations had nested selectors that were unnecessarily long were shortened, the
      elements these referred to only occured in one parent element so the extra specificity
      was discarded in favor of conciseness while preserving functionality

----- the order of some declarations were changed so that the order of the CSS page reflected
      the same order as their corresponding HTML elements

----- each element of the same type in the 'main' and 'aside' sections had the same CSS parameters,
      so the CSS declarations were consolidated to improve readability and make the code neater

