# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This challenge was to build a recipe page, with a focus on semantic HTML5.

### Screenshot

![Design preview for the Recipe page coding challenge](./design/desktop-preview.jpg)

### Links

- Solution URL: [Github](https://github.com/delroscol98/Omelette-Recipe)
- Live Site URL: [Github Pages](https://delroscol98.github.io/Omelette-Recipe/)

## My process

In my last two projects, the feedback that was given was focused on responsive design and the order of heading tags. In this project, those two were a focus as well as using appropriate semantic HTML5 tags. Once again I adopted mobile-first workflow, and used media queries to make the website responsive. Instead of using media queries to cater for mobile, I used media queries to cater to tablet and desktop.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

In this project, in addition to using semantic HTML5, I attempted to adopt the DRY (Don't Repeat Yourself) Method in my CSS. Below are some code snippets I'm proud of:

```html
<figure>
  <img src="./assets/images/image-omelette.jpeg" alt="omlette" />
</figure>
```

May be simple, but it's more semantic than using a div and using background-image to output an image.

```css
.recipe_ingredients,
.recipe_instructions,
.recipe_nutrition {
  margin-top: 2rem;
}

.recipe_ingredients ul,
.recipe_instructions ol {
  padding: 1rem 0rem;
  border-bottom: 1px solid var(--lightgrey);
}

.recipe_ingredients ul li,
.recipe_instructions ol li {
  font-size: 1.75rem;
  margin: 2rem 2rem 2rem;
  padding-left: 2rem;
}
```

Employing the DRY method for clean CSS

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

In future projects, I would like to continue using mobile-first workflow, semantic HTML, and responsive design. I'm not very familiar with tables and styling tables, so I'd like to explore them more. Additionally, I'd like to refine my ability to write clean code, maybe write some comments for better readability in my code.

### Useful resources

- [HTML Tables](https://www.w3schools.com/html/html_tables.asp) - This helped me to write HTML tables
- [HTML Lists](https://www.w3schools.com/css/css_list.asp) - This helped me to write and style HTML lists

## Author

- Frontend Mentor - [@delroscol98](https://www.frontendmentor.io/profile/delroscol98)
