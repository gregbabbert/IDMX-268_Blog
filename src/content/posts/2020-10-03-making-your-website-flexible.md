---
template: blog-post
title: Making Your Website Flexible
slug: making-your-website-flexible
date: 2020-10-02 21:03
description: Making your website flexible
featuredImage: /assets/markus-spiske-pwpvgq-a5qi-unsplash.jpg
---
    When making websites, one of the most important things nowadays is that your website is able to be viewed by different devices. In the past you could only access a website through a computer, which all had screens that were about the same size. Now you’re able to get on a website through your computer, tablet, phone, and even your refrigerator or watch. Because of their varying screen sizes websites often look different on each of these devices. To make your website accessible on different sizes of screens, web developers have to put media queries in their CSS so that for each screen size the font and widths of their elements all look correct.
          Media queries have to be done for a lot of different screen sizes, which can become a lot of work and fill your CSS with code. There’s got to be another way right? Well, recently some new functions were added to CSS to make your work easier. These functions are clamp, min, and max. These functions are used as a way to make it easier to scale websites so that as the website gets bigger and smaller their font and width also adjust accordingly. Let's look at the function max() first. Before when you wanted to set the width of your content you might make CSS code that looks like:

  

```
 body {
       width: 75%;
       max-width: 600px;
       }
```

    This makes the body of your website seventy-five percent of the screen, but once the website grows and reaches a width of six hundred pixels it stops there. With the max() function this can all be done in one line of code:

    

```
body {

    width: max(75%, 600px);

    }
```

    This one line of code does the same thing as the other two lines of code, which makes this function very useful. The max function can also be used for fonts, so that as you make your website’s screen bigger and smaller the words inside still look okay. The min function does the same thing as the max function, except it stops changing once the element gets to a minimum size.

    The final function I want to go over is the clamp function, which is even better than the min and max functions. The reason why it’s better is because it’s actually a combination of the two. The clamp function works by taking in three values: a min, a max, and a value that it should try to be. It doesn’t matter what order these numbers are in, there just have to be the three of them. How the function works is it sets the function to the middle value, and then as the screen size goes up or down the size of the element goes towards the min and max values. Once the size of the element reaches one of these values, it stops changing in size. These three functions are very useful and will help make web developers not have to use as much code.