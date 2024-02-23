# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [https://github.com/NicolasSilvaDA/social-links-profile]
- Live Site URL: [https://nicolassilvada.github.io/social-links-profile/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

With this challenge, I discovered that there's so much that I want to do and this is just the beginning. Those past years, I've been stuck on doing projects because I was insecure about my skills to do so, and now I'm willing to go further to hone my abilites and gather as many knowledge as possible to apply it on solutions in general. 

Below are some code snippets that I personally liked and wanted to share:


For the profile photo, I used a div instead of img because of the flexibility that it provides.

```html
<div id="prof-photo"></div>
```
```css
div#prof-photo {
    margin: auto;
    width: 200px;
    height: 200px;
    background-image: url("[image-url]");
    background-position: top;
    background-size: cover;
    border-radius: 50%;
}
```

While adjusting the buttons on the container, I felt like putting a flexbox on the main container wasn't the best solution because all the other elements would be modified by it, so instead of doing this, I put all the buttons inside a div and gave this specific element a flexbox, that way was the best I could think at the moment and it worked really well to me.

```html
<div id="buttons">
            <a class="btns" href="[github profile link]" target="_blank">GitHub</a>

            <a class="btns" href="[linkedin profile link]" target="_blank">LinkedIn</a>

            <a class="btns" href="[frontend mentor profile link]" target="_blank">Frontend Mentor</a>
</div>
```
```css
div#buttons {
    display: flex;
    flex-direction: column;
    align-items: center;
}
```


### Continued development

For my future projects, I want to be able to work with flexbox and gridbox more, which were concepts that I kept running from, and work on complex projects like building a site design, complex element animations, etc.


### Useful resources

- [W3Schools](https://www.w3schools.com/) - W3Schools helped me to remember how some elements and attributes work. I really recommend their site for people who usually have trouble remembering certain things in web development.


## Author

- GitHub - [@NicolasSilvaDA](https://github.com/NicolasSilvaDA)
- Frontend Mentor - [@NicolasSilvaDA](https://www.frontendmentor.io/profile/NicolasSilvaDA)
- LinkedIn - [Nicolas Silva](https://www.linkedin.com/in/nicolas-silva-araujo/)
