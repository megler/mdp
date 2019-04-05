## MDP

# Goal

An HTML experiement in RWD 2.0 utilizing CSS Custom Properties, CSS Calc, and multiple responsive typescales.

# What I've Done

- Semantic HTML
- CSS via SASS utilizing mixins, functions, and loops
- jQuery plugin for mobile navigation
- Pure CSS menu for non-mobile screensizes
- CSS Grid for site structure
- Flexbox for inner layout such as nav and gallery
- CSS Custom Properties to implement 3 different responsive type scales across multiple breakpoints
- CSS Calc to scale type up and down
- Responsive images
- Print media query that strips out color (CSS Filters) and layout

# Font and Typescale

I chose contrasting fonts for this site.  Maison du Pup was originally envisioned as a fashion house owned by a French dog named Jacques.  The Goldoni font looks French/Modern/Fashion, but would be overwhelming as body text.  The Sans Serif font was chosen to balance out the text, make it readable, and balance out the strong look of Goldoni.  Simple and clean.

I used 3 typescales across multiple breakpoints.  

Desktop = Major Third
Tablet = Minor Third
Phone/Sm Mobile = Major Second

My specific typescales were chosen from: https://type-scale.com/ 

The idea of using 3 typescales is to address heading size on smaller screens.  The Major Third creates large H tags that are overwhelming on smaller screens.  By scaling down on tablet and again on mobile, they look more natural in their respective setting. 

# What I've learned

This was mainly an exercise to learn CSS Custom Properties and their use in a SASS environment. Also how to create a responsive typescale that switches to a new typescale at pre-determined breakpoints.

While it was fun to create a pure CSS menu, likely I'll use vanilla Javascript or jQuery in production.  There's a cleaner distincion between the use of CSS (styling) and function (JS).  

As always, I'm not a designer.  Had this been an actual designer, the site would look better.  This site is designed to show front end dev skills, not art skill.

# What I'd like to improve

There are always ways to make the code more DRY.  I'm comfortable in SASS, but need to work on making code more consise will still being readable.  I will continue working with Custom Properties and Calc to improve my code.

# Link
https://megler.github.io/mdp/
