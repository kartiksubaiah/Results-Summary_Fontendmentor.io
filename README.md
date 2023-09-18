Results summary component solution.

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Building a result summary component by Fontendmentor.io.

Have Assumed 700px width for mobile device so that we don't have to scroll too much to see the mobile view. You can also zoom out a little and see the view.

### Screenshot

(./final-look_screenshot.jpg)

### Links

- Solution URL: [GitHub link](https://github.com/kartiksubaiah/Results-Summary_Fontendmentor.io/)
- Live Site URL: [GitHub Link](https://kartiksubaiah.github.io/Results-Summary_Fontendmentor.io/)

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

-My major learning here was make sure to have all the specifications with you like the font-sizes, color codes and if possible the distances between the elements as well.
There may be various ways of building this compopnent but must aim for clear, uniform and concise code rather than having multiple margin/padding-tops and bottoms.
-For some reason I did not feel using CSS Grid will make it easier but will try in future.
-For getting the gradients exactly as in the design/picture, it really takes CSS gradient mastering.
-A new thing I learnt was making custom cursor look. Below is the CSS code snippet I used to get a custom cursor look by using an image file in the project folder. I also found only SVGs were working for me. No PNGs etc:

<.big-box a:hover{
    background: linear-gradient(180deg, hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    cursor: url("./pointinghand.svg"), auto;
}>

-I ended up looking at the screen for a long time and also from close distance to see the transparencies of the colors. I'm still figuring the solution for eye strain because even with glasses with blue light reduction, my eyes still hurt.

### Continued development

I'd like try using CSS Grid for this project, lets see how that works.

### Useful resources

- [CSS-Tricks.com](https://css-tricks.com/using-css-cursors/) - This helped me to get customer cursor look. You just have to download an SVG file of a cursor from google.
- [w3Schools](https://www.w3schools.com/) - These guys have helped in various topics me forever. 

## Author

- Name- [P G Kartik Subaiah]
- Frontend Mentor - [@kartiksubaiah](https://www.frontendmentor.io/profile/kartiksubaiah)

## Acknowledgments

Thanks to "Coder Coder" youtuber for suggesting me Frontendmentor.io. Its been pretty good so far.
