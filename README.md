# order-summary-component-main
 Frontend Mentor Order Summary Card challenge
 
 # Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I used the philosophy of "mobile first" and that helped me to see the most complicated parts in the different screen sizes and to follow the guidelines of the general design of the project.

To begin with, I put the reference images of the design in "InkScape" and there I framed the main sections of the design.

With this design I proceeded to make the html framing.

For the CSS I used general classes that I could use on various elements and added "id" to the elements that needed their own style.

Finally I made the "media query" for the desktop version and the landscape position of the mobile version. For this I used the screen aspect ratio as it works best for all different radios.

I made final corrections and finished the project.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

An important learning from this project was in the initial layout. I first tried to capture the html directly, but this caused me to continually have to make corrections.
By doing a project layout before I started writing code helped me to finish the project faster.

Using  divs as a spacer also helped me give it the look I wanted without always relying on margins. 


```html
<div class="spacer"></div>
```
```css
.spacer {
    height: 3vh;
    width: 100%;
}
```
For the movile version I used relative units, this way the font size adapt to the screen without making a ton of media query.
```css
body {
    font-family: var(--font--global);
    font-size: 3.5vw;
    line-height: 1.5em;
    font-weight: 500;
    color: var(--neutral-desaturated-blue);
}
```
For the desktop version I used the 16px font-size especified in the proyect style-guide.

### Continued development

In this project I consider that I have several areas of opportunity, one of the most important is in the buttons, since I use "a" and I consider that the appropriate use is "button", it is something I want to correct.

### Useful resources

- [Resource 1](https://www.freecodecamp.org/news/css-flexbox-and-grid-tutorial/) - This helped me to realize the importance of planning how the objects on the page should be framed before applying the styles. I had some problems at the beginning but with this information I was able to do a proper markup for this project.
- [Resource 2](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) - I used the principle of "mobile first" and at the end I realized that using a @media with the width was not going to work correctly with this project. The information from w3schools helped me select the correct @media for the project. 
- [Resource 3](https://developer.mozilla.org/es/) - As always MDN is one the most valuables sources of information and I always use it when I have doubts about what I'm doing.


## Author

- Website - [Hector Enrique Sánchez Coronel](https://github.com/encoreOax)
- Frontend Mentor - [@encoreOax](https://www.frontendmentor.io/profile/encoreOax)
- Twitter - [@HectorCoronel81](https://www.twitter.com/HectorCoronel81)

## Acknowledgments

I just finish freecodecamp.org responsive web desing course and It really help me to remember and up date my knowledge of web development, I used to work 100% creating web-pages 15 years ago and the tecknology has change a lot. Many things that use to be impossible to make now is a piece of cake! 

I will continue in freecodecamp.org and learn more about application development because I love problem solving!