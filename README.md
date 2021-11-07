# Frontend Mentor - Huddle Landing Page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

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

## Overvoew

### The challenge

Users should be able to:

- View the optimal layour for the page depending on their device's screen size.
- See hover states for all interactive elements on the page.

### Screenshot

Desktop View
![](assets/img/desktop-1440.jpeg)

Tablet View
![](assets/img/tablet-view.jpeg)

Mobile View  
![](assets/img/mobile-view.jpeg)

Active State
![](assets/img/active.jpeg)

### Links

- Solution URL: [Huddle Landing Page Repo](https://github.com/JoshDagat/FM-Huddle-Landing-Page)
- Live Site URL: [Huddle Landing Page](https://joshdagat.github.io/FM-Huddle-Landing-Page)

## My process

I always start with getting the HTML done first. Then I worked my way down with the CSS.

Once I had the general layout done, I started tweaking with the media queries.

### Built with
- HTML
- CSS Properties
- Flexbox
- Mobile-first workflow

### What I learned

When I was working on the responiveness of the page I noticed some sections where there would be excessive space at the bottom.

```css
    .body {
        min-height: 100vh
    }
```

I learned that the code above isn't a one size fits all solution for good layout. There was no alternative to good media queries.

### Continued Development

The landing page's layout looks good on the different device simulators on Chrome. However, for Ipad PRO, there is massive space due to ```css .<selector> {min-height: 100vh}``` that I set.

I intend to study and look for a media query that will target this particular device.

## Author 
- LinkedIn - [Josuer](https://www.linkedin.com/in/josuer-bague/)
- Frontend Mentor - [FM Josuer Bague](https://www.frontendmentor.io/profile/JoshDagat)
