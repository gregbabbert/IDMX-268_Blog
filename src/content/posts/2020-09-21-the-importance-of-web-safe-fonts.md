---
template: blog-post
title: The Importance of Web Safe Fonts
slug: the-importance-of-web-safe-fonts
date: 2020-09-20 22:22
description: The importance of web safe fonts
featuredImage: /assets/brett-jordan-qrjvkj-os-m-unsplash.jpg
---
<!--StartFragment-->

Objectives: To explain what web safe fonts are, to explain why they’re important, and to give a safe way to use unsafe web fonts.



When planning how you want your webpage to look, one of the most important things to consider is your font. If you look on Google Fonts there’s a long list of amazing fonts to use, but you have to be careful. The more unique a font is, the more likely it won’t be supported by older operating systems. When this happens your font will automatically switch to Times New Roman, which looks pretty bad. This is why it’s important to use web safe fonts, which are fonts that are supported by most operating systems. Examples of web safe fonts are arial, serif, and sans-serif.

Using web safe fonts is a great way to guarantee that the page you designed is the page that the user will see, but you don’t have to choose a web safe font. By using the css property “font-family” you can choose a font that isn’t web safe, and then as a backup you can provide web safe fonts.



p {

font-family: "Times New Roman", Times, serif;

}



In the above example, the user has given their code a font of “Times New Roman.” Most operating systems have this font, but if not the code would then switch to Times, and then to serif if the system doesn’t have Times. This is a good css property to use if you want to try using fonts that aren’t web safe. With this information on the importance of web safe fonts, hopefully this now helps you design websites that are better for the user.



<!--EndFragment-->