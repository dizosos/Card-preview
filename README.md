# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

### Links

- Live Site URL: [https://prevcard.netlify.app]

## My process

- Start with creating HTML for the project
- After i created all containers for the project i start with CSS
- Import fonts and apply them
- Center the card
- Apply widths, heigths
- Apply colors, fonts, etc.
- Add media query for mobile devices
- Add footer with author name

### Built with

- HTML
- CSS
- Flexbox

### What I learned

I learned about border-box which helped with keeping 2 container(.img-container and .details-container) same size
```css
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
```
Also learned about media query when i was trying to make it work for mobile
```css
  @media  all and (max-width:600px)
```
One more thing i learned was positioning which i used to put my footer under the card container
```css
.card{
    border-radius: 10px;
    display: flex;
    max-width: 660px;
    margin: 0 1rem;
    background-color: white;
    position: absolute;
}

footer{
   position: relative;
   align-self: flex-end;
}
```
html
From my last project and from feedback i learned that my content should be contained in "main" attribute and also "footer" for side content just like author name.


### Continued development

I think i need to focus more on using flexbox because it is very handy to move things around but its also complex sometimes and i dont understand it very good yet

Another thing i need to work on is using correct units

## Author

- Frontend Mentor - [https://www.frontendmentor.io/profile/dizosos]