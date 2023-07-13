# Results-summary-component
Frontend Mentor poject. Responsive layout with two cards

## Table of contents

 ## Overview
  ### The challenge
  ### Screenshot
  ### Links
 ## My process
  ### Built with
  ### What I learned
  ### Continued development
  ### Useful resources
 ## Author
 ## Acknowledgments

## Overview

  ### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

  ### Screenshot
[](./result_bottom-mobile.png)

  ### Links

- Solution URL: https://github.com/Arkadiusz-coder/Results-summary-component
- Live Site URL:

## My process

  ### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS variables
- CSS Grid
- Mobile-first workflow

  ### What I learned
 
I learned a lot about responsiveness; how to fix given size of a div to stay the same despite change of the screen sizes; how to create nice looking layout with minimal use of divs.

I used for the first time extendend version of bordr-radius
```CSS``
 .result_card
{
    border-radius: 0px 0px 20px 20px;
}
``

and for the first time I made perfectly round element with aspect-ratio, with fixed size and gradient color
 
 ```CSS``
.total_score
{
    max-width: 164px;
    background-image: linear-gradient(180deg, var(--dark-blue), var(--sky--blue));
    border-radius: 50%;
    aspect-ratio: 1 / 1;
    margin: 0 auto;
    padding: 1rem;
}
``

  ### Continued development

I need to focus on proper HTML landmarks and better use of images in svg format. 
  
  ### Useful resources

Course on responsive layouts
https://courses.kevinpowell.co/view/courses/conquering-responsive-layouts

YT channel of K. Powell
https://www.youtube.com/watch?v=KqFAs5d3Yl8&ab_channel=KevinPowell
  
## Author

GitHub: https://github.com/Arkadiusz-coder/Arkadiusz-coder
Frontend Mentor: https://www.frontendmentor.io/profile/Arkadiusz-coder

## Acknowledgments

I am greatly thankful to Kevin Powell, due to his YT channel and his course on Responsive Layout I learn a lot about: 
using CSS variables;
trick with border-radius: 0 0 20px 20px;
that with {margin: 0 auto;} you can center elements;
differences and good practices with flex and grid.

Three mouths ago I creat that project along with him, couse he doing it on YT. Finally I felt ready to do it on my own, from scratch and I see how much I learned on span oof those three mounth.  



