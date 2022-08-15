# EventKey-Codes

This is apart of the 50 projects in 50 days challenge and is the eleventh project.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

- To work with the `keydown` feature so that the key, keyCode and code will appear on the screen depending on which key was pressed. The challenge involves HTML, CSS and Javascript.

### Screenshot

# Mobile Preview 

![screenshot](https://github.com/romila2003/EventKey-Codes/blob/main/Mobile%20preview.PNG)

# Mobile Preview - Active

![screenshot](https://github.com/romila2003/EventKey-Codes/blob/main/Mobile%20preview%20-%20active.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/EventKey-Codes/blob/main/Desktop%20preview.PNG)

# Desktop Preview - Active

![screenshot](https://github.com/romila2003/EventKey-Codes/blob/main/Desktop%20preview%20-%20active.PNG)

### Links

 - Source code: [https://github.com/romila2003/EventKey-Codes](https://github.com/romila2003/EventKey-Codes)
 - Live website: [https://eventkey-codes.netlify.app/](https://eventkey-codes.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Vanilla Javascript
- Flexbox

### What I learned

This was an interesting project because I realised the use of keycodes within security questions that require random keys. It was fun to learn a new concept that I could potentially use in the future.

Javascript - `keydown`:

```javascript

const insert = document.getElementById("insert");

window.addEventListener("keydown", (e) => {
    insert.innerHTML = `
    <div class="key">
        ${e.key === " " ? "Space" : e.key}
        <small>event.key</small>
    </div>
    <div class="key">
        ${e.keyCode}
        <small>event.keyCode</small>
    </div>
    <div class="key">
        ${e.code}
        <small>event.code</small>
    </div>`
});

```

### Continued development

For future developments, I should implement the features/concepts learned over the last few projects and future projects, into practical projects/challenges such as the frontendmentor.io projects.


## Author

- Twitter - [@romila003](https://www.twitter.com/romila003)
- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
