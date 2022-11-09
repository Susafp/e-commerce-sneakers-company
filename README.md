# Frontend Mentor - E-commerce product page solution

This is a solution to the [E-commerce product page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ecommerce-product-page-UPsZ9MJp6). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Ux](#ux)
  - [Built with](#built-with)
  - [Testing](#testing)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Deployment](#deployment)
  - [Useful resources and acknowledgements](#useful-resources-and-acknowledgements)
- [Author](#Author)

## Overview

### The challenge

The challenge was to build out an e-commerce product page and get it looking as close to the design as possible.

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Open a lightbox gallery by clicking on the large product image
- Switch the large product image by clicking on the small thumbnail images
- Add items to the cart
- View the cart and remove items from it

### Screenshot

![E-commerce Product Page](images/responsive.png)

### Links

- Solution URL: (https://github.com/Susafp/e-commerce-sneakers-company.git)
- Live Site URL: (https://susafp.github.io/e-commerce-sneakers-company/)

## My process

### UX

The design guidelines for this website can be found [here](design-guideline)
The style guide for this website can be found [here](design-guideline/style-guide.md)

### Built with

- [**Visual Studio Code**](https://code.visualstudio.com/)
   - My development environment of choice to work on this project.
- [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - To get all my elements in and set the project structure.
- [**CSS3**](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - To add the styles needed to achieve a look as similar as possible to the one provided in the design-guideline.
- [**JavaScript**](https://www.javascript.com/)
    - I've used **JavaScript** to add functionality to several elements, as: the image gallery, view, add or remove items from the Cart.
- [**Canva**](https://www.canva.com/en_gb/)
    - The design tool that I've used to create a presentation image of my solution for this challenge (images/responsive.png).
- [**Git**](https://git-scm.com/)
    - I've used **Git** as a version control system to regularly add and commit changes made to project in Visual Studio Code, before pushing them to GitHub.
- [**GitHub**](https://github.com/)
    - I've used **GitHub** as a remote repository to push and store the committed changes to my project from Git. I've also used GitHub pages to deploy my website in a live environment.

### Testing

I've mainly used Microsoft Edge's Development tools to constantly test each new piece of code to ensure that it appeared as defined for screens 375px and 1440px. I also tested my website with Google Chrome and Mozilla Firefox.

#### HTML, CSS and JavaScript Code Validation

To test this website, I used:

- [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) to validate my HTML code. 
Outcome: Two warnings, no errors.

- [W3C CSS Validator tool](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate my CSS code.
Outcome: 
"Line 22 - Value Error : font-family is an incorrect operator : 'Kumbh Sans' sans-serif" (a comma was missing).
"Line 726 - Value Error : background-color none is not a background-color value : none" (it should be "white").

- [Code Beautyfy JavaScript Validator tool](https://codebeautify.org/jsvalidate) to validate my JavaScript code.
Outcome: 
Line 1 - Unexpected 'const': "const menu = document.querySelector('.menu');"
This prevents the scanning of the rest of the document:	"Stopping. (0% scanned)"

- [Microsoft Edge - Lighthouse tool](testing/lighthouse-report.pdf)
Outcome: 
Performance: 99%
Accessibility: 94%
Best Practices: 100%
SEO: 100%

### What I learned

- How to code and position the little "cart-count" feature above the shopping cart   (div="cart-count hidden").
- I've learned a new and simplier way to code an Hamburger menu, and
- How to include svg images and the tricks on how to be abble to change its original colors.

### Continued development

- Since it is not my strongest point, I will benefit from continuing to learn and practice on how to add functionality to elements with JavaScript.

### Deployment

The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

1. Loaded the terminal window in my Visual Studio Code workspace.
2. Initialised Git using the `git init` command.
3. Added all files to the Staging area (Git) using the `git add .` command.
4. Committed the files to Git using the `git commit -m "Initial commit"` command.
5. Created a new repository in GitHub called 'JS-Milestone-two'.
6. Copied the below code from GitHub into the terminal window in my Visual Studio Code workspace:

```git remote add origin https://github.com/Susafp/e-commerce-sneakers-company.git```,
```git branch -M main```,
```git push -u origin main```.

7. Entered my GitHub username and password to push the files from Git to GitHub.
8. Went into 'Settings' on my repository page in GitHub.
9. Selected the 'main branch' option under the 'GitHub Pages' section.
10. Ran several regular commits throughout my project.

### Running Code Locally

To run my code locally, users can download a local copy of my code to their desktop by completing the following steps:

1. Go to [my GitHub repository](https://github.com/Susafp/e-commerce-sneakers-company.git).
2. Click on 'Clone or download'.
3. Click on 'Download ZIP'.
4. Once downloaded, extract the zip file's contents and run my website locally.

### Useful resources and acknowledgments

- [Picozu.com](https://www.picozu.com/how-to-change-the-color-of-an-svg-image) - In here I found information about how to change svg images color.
- [Ellie Judge](https://github.com/EllieJ87) - Ellie is a former Learning People student that was happy for me to look into her project to give me an inicial inspiration for possible ways on how to approach this challenge.
- [FreeCodeCamp - Build a Shopping Cart with JavaScript](https://youtu.be/cT_ZYrS3tKc) - This tutorial helped me on how to add functionality to my shopping cart.
- [Sergii Moroz](https://github.com/sergii-moroz/E-commerce_product_page/blob/main/index.html) - This helped me with the Javascript side of the Cart.

A big thank you to all the people mentioned above that made available their knowledge and by doing so it helped me immensely with this challenge.
A big thank you to my course mentor Scott Nnaghor for beeing there to help and support in case I needed.

## Author

- Frontend Mentor - [@Susafp](https://www.frontendmentor.io/home)
- Github - [Susafp](https://github.com/Susafp)
- Linkedin - [Susana-fP] - (https://www.linkedin.com/in/susana-fp/)


