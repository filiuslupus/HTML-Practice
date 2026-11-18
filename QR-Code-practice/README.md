# Frontend Mentor - QR code component solution

Personal solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

This is my initial attempt into formalizing my knowledge base of HTML/CSS (and eventually JS). I've been able to
read and write HTML/CSS for over a year at this point, born of certain work needs, but purely based on the work
of others (i.e., I need a base to work with in order to expand/modify properties, styles, etc., but I couldn't
write a single page from scratch to save my skin). Seeing as I could do some pretty advanced things based on the
feedback of my coworkers, instead of half-a**ing things I decided to give frontend development a shot and whole-a**
things. A month or so later of reading documentation and banging my head against the wall here I am.

The most challenging part of this challenge was centering the QR code card itself, as my previous experience
helped make short work of the borders, colors, etc. I would say it took me around an hour an a half to finish this,
with over half of that time tying myself into knots trying to figure out how to center things.

### Screenshot

[Solution screenshot](QR-code-solution.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

I started by expanding the HTML document: Adding the stylesheet link, the font to use with @import, adding a div,
two p tags, and the img tag for the QR code image itself. I also decided to add an id to the QR code component div,
as though it was not necessary for this exercise, based on my currently limited understanding of HTML, on real world
applications this would've helped to dinstinguish it from other divs (I think). Likewise, I decided to add a class
to each p tag, to be able to add specific custom CSS to each p tag, due to required style differences. The last
element I added was a <br> in the middle of the "Improve your front-end skills" p tag in order for it to cleanly
break into two lines as per the reference images.Overall, leaving the HTML to a state I found satisfactory took me a
few minutes.

The painful part came with the CSS sheet. I quickly set the background color and max-width for the card, before jumping
to what I felt wold be the most difficult part of the CSS elements, which was centering and aligning the card itself,
as well as its contents. After some trial and error (plus reviewing the CSS reference for the justify and align attributes),
I managed to get everything lined up horizontally, but not vertically. With that achieved, I jumped into adding the styles
for the text and the rounded corners for the card, and spent the rest of the challenge turning myself into a pretzel, and
jumping back and forth between the CSS reference and Visual Studio. In the end I managed to get the d*** thing vertically
centered, but i do not really like the way I did it.

About the only question I have is whether my solution follows best practices or not, which I guess encompasses the question
of whether the way I centered things was the most optimal one.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Visual Studio Code
- htmlcheatsheet.com/css/
- Google fonts

### What I learned

- I got a better understanding of Flexbox with this. I think.

### Continued development

- I still got a long way to go to truly understand Flexbox.
- I REALLY need to learn CSS Grid.

### Useful resources

- [Mozilla's CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS) - To revisit and explore new concepts; I found margin-inline this way, and found it to be quite handy.
- [HTML Cheat Sheet](https://htmlcheatsheet.com/css/) - A "shorthand" way for me to recall concepts that I know what they do when looking at them but forget the name (e.g. selectors, appropiate syntexis to include an external CSS file, etc.)

## Author

- Github - [filiuslupus](https://www.github.com/filiuslupus)
- Frontend Mentor - [@filiuslupus](https://www.frontendmentor.io/profile/filiuslupus)