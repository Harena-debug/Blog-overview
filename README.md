# Frontend Mentor -Blog Preview Card Solution

This is a solution to the [Blog Preview Card Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

-[Preview](#preview)
  -[The challenge](#the-challenge)
  -[Screenshot](#screenshot)
  -[Links](#links)
-[My process](#my-process)
-[Built with](#built-with)
-[What I learned](#what I learned)
  -[Continued development](#continued-development)
  -[Useful resources](#useful-resources)
  -[AI collaboration](#ai-collaboration)
-[Author](#author)
-[Acknowledgments](#acknowledgements)


## Overview

Responsive blog preview card created as part of the Frontend Mentor challenge. 
This project puts CSS variables, hover effects, 
and design with drop shadows.


### The challenge
Create an interactive blog map with:
-Design faithful to the model
-Hover effect on map
-Responsive on all devices
-Use of CSS variables

### Screenshot

![Blog map preview](image.png)

Responsive blog card with hover effect and drop shadow.


### Links

-Solution URL: [Add solution URL here](https://your-solution-url.com)
-Live Site URL: [Add Live Site URL Here](https://your-live-site-url.com)
## My process

My process for creating this blog is below:

### Built with

I used the following technologies to create this blog:

-HTML for semantics
-CSS Flexbox for blog centering
-Responsive CSS for blog adaptation on all devices
-CSS:hover to add a small hover effect

### What I learned
In this second project, I learned the following concepts:

-CSS variables -Advantage: change a color everywhere by modifying
a single line
```css
:root{
      --weight : 800;
      --radius : 15px;
      --main-color : hsl(47 , 88% , 63%);
    }
body{
      background-color: var(--main-color);
      font-family: "Figtree" , sans-serif;
    }
.learning{
      background-color: var(--main-color);
      display: inline-block;
      padding: 4px 12px;
      text-align: center;
      font-weight: var(--weight);
      margin-top: 15px;
      border-radius: 5px;
    }
```

-The principle of the hover effect

```css
article:hover{
      transform: scale(1.05);
    }
article{
      background-color: hsl(0, 0%, 100%);
      max-width: 21.875rem;
      padding: 20px;
      border-radius: var(--radius);
      line-height: 30px;
      box-shadow: 8px 8px 0px #000;
      border: 2px solid #000;
      transition: transform 500ms;
    }
```

### Développement continu
I managed to use a small hover effect in this project. But I would like to focus a little more on complex animations in the next challenge.


### Useful resources

-[W3Schools](https://www.w3schools.com/) -Always the best place to learn and code at the same time. 


### AI collaboration

I collaborated with IA in the following way:

-The tools used: always Chatgpt and Claude.
-How I used them:
  -Help for centering the “Learning” text
-Explanation of "display: inline-block"


## Author

-Website -[Harena-debug](https://github.com/Harena-debug)
-Mentor Frontend -[@Harena-debug](https://www.frontendmentor.io/profile/Harena-debug)
## Acknowledgments

Thanks to **Frontend Mentor**for this challenge which allowed me to discover the 
CSS variables and hover effects.

Thanks also to the Frontend Mentor community for the shared solutions 
which inspired me for the “neumorphic” box-shadow effect.