# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

<p float="left">
<img src="https://github.com/aviralsharma07/product-preview-card-component/blob/0df2dbaf209cfbdab46bdd3d2474c32b1339f8a1/prodmobile.png" width="25%" height="350px">

<img src="https://github.com/aviralsharma07/product-preview-card-component/blob/0df2dbaf209cfbdab46bdd3d2474c32b1339f8a1/proddesktop.png" width="72%" height="350px">
</p>

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/responsive-3-column-preview-card-using-flexbox-0-YjHGFxc6)
- Live Site URL: [3 Column Preview Card](https://3col-card-component.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Netlify

### What I learned

1. Adding Different Images for Mobile and Desktop Version through Image element and srcset attribute.
```html
      <picture class="section product-photo">
        <source srcset="/images/image-product-mobile.jpg" media="(max-width:600px)">
        <img src="/images/image-product-desktop.jpg" alt="Perfume Image">
      </picture>
```
2. Use of gap to give spacing between Flex children.
3. 
### Continued development

Moving ahead:
- I will learn to use media queries to make sites responsive in Mobiles.
- I want to create more complex projects by improving grasp on Flexbox, positioning and typography.

### Useful resources

- [Learn FlexBox - Kevin Powell](https://youtu.be/u044iM9xsWU) - This Video by the CSS Guru Kevin helped me to understand the basics of FlexBox.
- [CSS Course on FreeCodeCamp](https://youtu.be/OXGznpKZ_sA) - This is a amazing all in one course for CSS by Dave Gray.
- [Netlify](https://www.netlify.com/) - Netlify allows you to deploy your project live on web for free.
- [Solutions on Frontend Mentor](https://www.frontendmentor.io/solutions) - I refer other's solution to same project when I got stuck.

## Author

- Twitter - [_aviral07](https://www.twitter.com/_aviral07)
- Website - [Aviral Sharma](https://github.com/aviralsharma07)
- Frontend Mentor - [aviralsharma07](https://www.frontendmentor.io/profile/aviralsharma07)
- Blogs - [My Technical Blogs](https://codedamn.com/news/author/aviralsharma)

