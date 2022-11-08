# news-homepage
## Table of contents

-   [Overview](#overview)
	-   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
    -   [Useful resources](#useful-resources)
-   [Author](#author)

## Overview

### Links

-   Card URL: [Vercel URl](https://testimonials-grid-section-nu-mocha.vercel.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid

### What I learned

```css
@import url("https://fonts.googleapis.com/css?family=Inter:400,700,800&display=swap");
```
Here I decided to add a google font using css. I also found out about display=swap feature. The browser will initially show a fallback font, then once the Google Font has downloaded it will swap the fonts.

```html
<hr class="new__hr" />
```
Here I used hr for the first time to make a horizontal line. 

```css
.header {
	position: sticky;
	top: 0;
}

.nav {
	width: 100%;
	height: 100%;
	position: fixed;
}
```
This article really helped me understand the position feature.
```html 
<ul class="nav__menu">
	<li><a href="#home">Home</a></li>
	<li><a href="#new">New</a></li>
	<li><a href="#popular">Popular</a></li>
	<li><a href="#">Trending</a></li>
	<li><a href="#">Categories</a></li>
</ul>
```
Here I learnt what a href="#" is uded for. A hash - `#` within a hyperlink specifies an HTML element id to which the window should be scrolled.
href="#some-id" would scroll to an element on the current page such as <div id="some-id">, href="//site.example/#some-id" would go to site.example and scroll to the id on that page.
```html
<script src="menu.js"></script>
```
In this one I learnt how to add a js file to my project
```css
.bar {
	display: block;
	width: 25px;
	height: 3px;
	margin: 5px auto;
	-webkit-transition: all 0.3s ease;
	transition: all 0.3s ease;
	background-color: var(--clr-dark);
}
```
I also found out that the term 'webkit' is used in the CSS syntax for rendering content in Safari and Chrome browsers. Webkit code may need to be added in CSS to ensure it renders correctly on Chrome and Safari due to the lack of cross-compatibility.
```css
picture {
	width: 100%;
}

.home__image {
	width: 728px;
	max-width: 100%;
}
```
I don't why it took me so long to figure out how to make an img responsive, but now that I know how to deal with it, I won't have to struggle with it in my future projects. 
### Continued development

In my future projects I really want to have more pracice with:
-   Flexbox
-   CSS Grid

### Useful resources

-   [W3Schools](https://www.w3schools.com/) - This one really helps me out every time I have difficulty with any css property.
-   [CS50](https://www.youtube.com/watch?v=NcoBAfJ6l2Q&ab_channel=CS50) - This YouTube channel has countless useful videos. I tend to watch it when I have troubles with Git.
-   [cssgenerator.org](https://cssgenerator.org/) - Here are some useful css tools.
-   [LogRocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/) - This article helped me create a responsive mobile menu with CSS without JavaScript.
## Author

-   LinkedIn - [Daniil Kalugin](https://www.linkedin.com/in/daniil-kalugin)
-   Twitter - [@BeingMyselfFlow](https://www.twitter.com/BeingMyselfFlow)
