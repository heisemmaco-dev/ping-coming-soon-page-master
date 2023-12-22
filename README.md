# Frontend Mentor - Ping coming soon page solution

This is a solution to the [Ping coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ping-single-column-coming-soon-page-5cadd051fec04111f7b848da). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  
  - [Screenshot](#screenshot)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

### Screenshot

<img src="/design/desktop-design.jpg">
<img src="/design/mobile-design.jpg">

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Submit their email address using an `input` field
- Receive an error message when the `form` is submitted if:
	- The `input` field is empty. The message for this error should say *"Whoops! It looks like you forgot to add your email"*
	- The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Please provide a valid email address"*

### Links
<a href="https://heisemmaco-dev.github.io/ping-coming-soon-page-master/">Live Site</a>

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- javascript

### What I learned

In this project, I've gained knowledge about validating email addresses and performing form validation using JavaScript 

```html
<h1>Some HTML code I'm proud of</h1>
<main>
<section>
<img>

<button>claim</button>
```

```css
.proud-of-this-css {
  :hover
  padding 
  display: grid
}
```
```js
/* To validate an email */
function valid(email) {
    const re = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;

    return re.test(String(email).toLocaleLowerCase());
}
```

### Continued development

I'd like to deepen my understanding of using JavaScript to manipulate the DOM, improving my knowledge of JavaScript syntax for modifying the appearance and functionality of a webpage's frontend. Can you assist me in refining these skills?"

## Author

- Frontend Mentor - [@Moderateemmaco](https://www.frontendmentor.io/profile/Moderateemmaco)
- Twitter - [@heisemmaco-dev](https://www.github.com/heisemmaco-dev)
