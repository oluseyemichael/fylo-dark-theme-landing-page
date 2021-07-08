# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
This is a CSS task from side hustle internship 3.0. 
### The challenge
The challenge is to build out a landing page from frontend mentor and get it looking as close to the design as possible.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700&family=Raleway:wght@300;400;500;600;700&display=swap' - For styles


### What I learned

I learnt how to properly use CSS flexbox and Grid layout. I also learnt how to make my site responsive across all devices.

```html
<h1>Some HTML code I'm proud of</h1>
<div class="features-item">
                <div class="features-item-head">
                  <img src="./images/icon-security.svg" alt="icon-security">
                </div>
                <div class="features-item-body mt-2">
                    <h3> Security you can trust</h3>
                    <p> 2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.</p>
                </div>
            </div>

            <div class="features-item">
                <div class="features-item-head">
                  <img src="./images/icon-collaboration.svg" alt="icon-collaboration">
                </div>
                <div class="features-item-body  mt-2">
                    <h3> Real-time collaboration</h3>
                    <p> Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.</p>
                </div>
            </div>

            <div class="features-item">
                <div class="features-item-head">
                  <img src="./images/icon-any-file.svg" alt="icon-any-file">
                </div>
                <div class="features-item-body  mt-2">
                    <h3> Store any type of file</h3>
                    <p> Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.</p>
                </div>
```
```css
.proud-of-this-css
@media (max-width: 1000px) {
    header {
        padding: var(--padding-sm);
    }

    header img,
    footer img {
        width: 100px;
        height: auto;
    }

    section {
        padding: var(--padding-sm);
    }

    .intro>div,
    .features-item {
        width: 100%;
    }

    .testimonial,
    .productive {
        flex-direction: column;
    }

    .features-item {
        padding: 2rem 0;
    }

    .productive-content {
        margin-top: 2rem;
        padding: 0;
    }

    .testimonial-item {
        margin-left: 0;
        margin-top: 3.5rem;
        width: 80%;
    }

    .signup-item {
        width: 80%;
        padding: 2.5rem 2rem;
    }

    .signup-form {
        flex-direction: column;
    }

    .input-block {
        max-width: 100%;
        width: auto;
    }

    .btn-block {
        max-width: 100%;
        width: auto;
        min-width: 100%;
        margin-top: 1rem;
        margin-left: 0;
    }

    .contact-info {
        padding: var(--padding-footer-tablet);
        grid-template-columns: 100%;
        grid-template-rows: repeat(6, auto);
        grid-template-areas: "logo""location""contacts""links""social"" attribution";
    }

    .contact-info>div,
    .contact-info>nav {
        padding: 1rem 0;
    }

    .contact-info-contacts {
        align-items: flex-start;
    }

    .contact-info-links {
        flex-direction: column;
        justify-content: flex-start;
    }

    .contact-info-links-list:first-child {
        margin-bottom: 1rem;
    }

    .contact-info-social-links {
        justify-content: center;
    }
}

@media (max-width: 375px) {
    section {
        padding: var(--padding-sm);
    }

    .signup-item {
        min-width: 50%;
        max-width: 70%;
    }

    .contact-info {
        padding: var(--padding-footer-mobile);
    }
}
```


### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@Oluseye M. Olusegun](https://www.frontendmentor.io/profile/oluseyemichael)

