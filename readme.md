# Frontend Mentor - Sunnyside agency landing page solution


This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
Sunnyside is a creative brand  that helps business owners package, transform and present thier brand in an appealing way. Thier primary goal is to make your brand stand out positively, the brand has creatives teams whose main agenda is the success of your brand.


### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot
![](./images/Screenshot%202022-08-28%20171241.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Rasheedatj/Sunnyside)
- Live Site URL: [Add live site URL here](https://rasheedatj.github.io/Sunnyside/)

## My process

I structed the general layout using css gridlayout and I used flexbox for the sub- structures. I used grid row to readjust the positioning of the grid items on mobile screen, i also used grid auto row to manipulate the heights to my preference. The sharp edge over the mobile menu was gotten with pseudo element and clip path.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- I learnt how to use grid effectively
- I learnt some new grid properties like grid-auto-row, minmax e.t.c
- I leanrt how to make grid layout responsive 
- How to position grid items
- Major diffence between grid and flex-box and also when to used them
- How to center an abosolute div

```html

          <div class="Thomas">
            <img src="./images/image-thomas.jpg" alt="thomas avatar" />
            <p class="good_word">
              Sunnyside's enthusiasm couples with thier keen interest in our
              brand's success made it a satisfying and enjoyable experience.
            </p>
            <h2>thomas s.</h2>
            <p class="post">chief operating officer</p>
          </div>
```

```css
.hamburger_header::after{
    content: '';
    position: absolute;
    width: 40px;
    height: 40px;
    background-color: rgb(255, 251, 249);;
    top: 0;
    right: 0;
    transform: translateY(-98%);
    clip-path: polygon(100% 0, 0% 100%, 100% 100%);
}

```

```js
btn.addEventListener("click", () => {
        nav.classList.toggle("open");
        btn.classList.toggle("open_btn");
      });
```

### Useful resources

- [Grid youtube tutorial](https://youtu.be/0xMQfnTU6oo) - This helped me understand grid layout. I really liked this pattern and will use it going forward.
- [Clip path generator](bennettefeely.com/clippy/) - This is an amazing websitr which helped get the edge of my hamburger menu. I'd recommend it to anyone still learning CSS.

## Author

- LinkedIn - [Rasheedat](https://www.linkedin.com/in/rashedat-jinadu-066078227)

- Twitter - [@Rashedatj](https://www.twitter.com/Rashedatj)