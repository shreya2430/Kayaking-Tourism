# Assignment 4 - Layout and SCSS

## Project Overview

The main objective of this assignment is to demonstrate the use of SCSS features (variables, mixins, inheritance, control statements, and functions) while creating a modular and maintainable stylesheet. The layout uses CSS positioning, Grid, and Flexbox to align with the design from Assignment 2.

## Features

- **SCSS Conversion**: The SCSS is organized into multiple files based on UI components, common elements, and themes for a cleaner structure.
- **Grid and Flexbox Layout**: The layout is implemented using CSS Grid and Flexbox to ensure flexible and responsive positioning.
- **Modular Structure**: SCSS files are divided into smaller, well-organized parts for maintainability.
- **SCSS Features**:
  - **Variables** for consistency and reusability.
  - **Mixins** for reusable CSS code patterns.
  - **Inheritance** to reduce code duplication.
  - **Control Statements** for dynamic CSS generation.
- **Fixed Navigation Bar**: The navigation bar is fixed at the top of the viewport for easy access during scrolling.
- **Code Documentation**: SCSS code is documented with comments for clarity and to explain key decisions.

## Technologies

- HTML5
- SCSS (compiled to CSS using SASS)
- CSS Grid & Flexbox
- NPM for build tools

## File Structure

```bash
|--images/
|-- scss/
    |-- _footer-section.scss
    |-- _hero-section.scss
    |-- _kayak-tourist-place-section.scss
    |-- _kayaking-section.scss
    |-- _mixins.scss
    |-- _navbar.scss
    |-- _our-mission-section.scss
    |-- _promotion-section.scss
    |-- _review-section.scss
    |-- _tour-section.scss
    |-- _typography.scss
    |-- _variables.scss
    |-- _form.scss
    |-- main.scss
|-- Home.html


## How to Run the Project

1. Clone the repository using the GitHub Classroom link.
2. Make sure you have node and npm installed in your system then do `npm i --save-dev sass` to ensures the SCSS compiler (SASS) is installed as a dev dependency.
3. In package.json, under the "scripts" section, add the following line `"sass": "npx sass --watch scss/main.scss dist/main.css"`
4. Use `npm run sass` to compile SCSS to CSS.
5. Open `Home.html` in a browser to view the layout.

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/hC2sRxHe)

