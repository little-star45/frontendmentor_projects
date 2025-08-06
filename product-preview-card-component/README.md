# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Vite
- Tailwind CSS
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Tailwind 4.0 @theme @layer

```
css
@theme {
    --font-family-monteserrat-sans: 'Montserrat', sans-serif;
    --font-family-monteserrat: 'Montserrat', serif;
    --font-family-fraunces: 'Fraunces', serif;
    --font-size-body: 14px;
    --font-weight-fat: 700;
    --font-weight-slim: 500;
    --color-primary-green-500: hsl(158, 36%, 37%);
    --color-primary-green-700: hsl(158, 42%, 18%);
    --color-neutral-blackCustom: hsl(212, 21%, 14%);
    --color-neutral-greyCustom: hsl(228, 12%, 48%);
    --color-neutral-creamCustom: hsl(30, 38%, 92%);
    --color-neutral-whiteCustom: hsl(0, 0%, 100%);
    --breakpoint-sm: 550px;
}

@layer components{
    .attribution { 
        font-size: 11px; text-align: center;
        padding: 1rem;
    }
    .attribution 
        a { 
        color: hsl(228, 45%, 44%); 
    }
}

```

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
