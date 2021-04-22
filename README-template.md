# Frontend Mentor - Fylo landing page with two column layout solution

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshot)
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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshots

<img src="Fylo-mobile.png" alt="mobile solution" width="300px"/>

<img src="fylo-desktop.png" alt="desktop solution" width="600px"/>

### Links

- Solution URL: [solution](https://github.com/pawelpikus/fylo-landing-page)
- Live Site URL: [live site](https://pawelpikus.github.io/fylo-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

With this challenge I have trained and revised the concept of Responsive Web Design. I tried to push the requirements of this challenge a little bir further and build a fully responsive design. In particular: 

- the concept of desktop-first markup, putting content into semantic, logical chunks and laying it out with flexbox, whenever I could (flexbox rules!), e.g.:    

```html
<section class="section section-cta">
      <div class="container d-flex">
        <div class="cta-primary">
          <h1 class="section-title">All your files in one secure location, accessible anywhere.</h1>
          <p>Fylo stores your most important files in one secure location.
            Access them wherever you need, share and collaborate with friends,
            family, and co-workers.</p>
          <form class="cta-form">
            <input class="cta-input" type="email" required placeholder="Enter your email...">
            <input class="cta-btn" type="submit" value="Get Started">
          </form>
        </div>
        <img class="cta-img" src="./images/illustration-1.svg"
          alt="a huge file, a man and a woman inserting documents into it">
      </div>
    </section>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```
### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
