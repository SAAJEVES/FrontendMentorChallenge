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


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries


### What I learned

Coding esoteric challenges usually help me think deep and even have a deeper understanding on some tags. Take for example the 'a' (anchor) tag element, analysising this project made me discover that one can add padding to it and make it look like a button. Before now, I usually insert my anchor tag in a div tag. The problem I usually face is not been able to achieve that hover effect having styling (ie giving it a background-color) the div tag. Whenever I hover on the anchor tag (ie the words within ), the cursor changes to pointer but immediately I adjust the cursor from the words, the cursor goes back to normal. If hover over the anchor tags in this project and also the background, the cursor is same.

To see how you can add code snippets, see below:

```html
<a href="#" id="link1">Proceed to Payment</a>
```
```css
main > #link1{
    color: #fff;
    text-decoration: none;
    text-align: center;
    line-height: 27px;
    width: 60%;
    padding: 3px 20px 3px 20px;
    margin: 10px auto 10px auto;
    border: 0 solid hsl(245, 75%, 52%);
    border-radius: 8px;
    background-color: hsl(245, 75%, 52%);
    display: block;
}



main > #link1:hover{
    background-color: hsla(245, 75%, 52%, 0.548);
    box-shadow: 4px 2px 3px 3px hsl(225, 100%, 98%);
}
```

### Continued development

There are areas I do want to have continued development like in terms of making website responsive especially in the media query which is a major setback for me. Luckily for me, in this project I was quite better in it than before.


### Useful resources
A lot of resources was helpful not just in this project but from the beginning of my learning of web development.
- (https://www.w3schools.com) 

- (https://www.freecodecamp.com)

- (https://www.youtube.com)

- And lots more. Surely, I will always recommend them days in and days out


## Author

- Github - (https://github.com/SAAJEVES)
- Frontend Mentor - (https://www.frontendmentor.io/profile/SAAJEVES)
- Twitter - (https://www.twitter.com/saajeves)
- LinkedIn - (https://www.linkedin.com/in/samuel-ajagun-020283150)


## Acknowledgments

I would love to acknowledge a very good friend of mine (https://github.com/wisdomosara) for his immense contribution on helping me in this project. You are well appreciated.
