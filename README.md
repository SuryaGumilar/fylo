## Frontend Mentor - Fylo landing page with two column layout solution


This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor]
(https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Table of contents


  
- [The challenge](#the-challenge)
  
  
- [Links](#links)

- [My process](#my-process)
  
- [Built with](#built-with)
  
- [What I learned](#what-i-learned)
  
- [Continued development](#continued-development)
  
- [Author](#author)


### The challenge


Users should be able to:


- View the optimal layout for the site depending on their device's screen size

- See hover states for all interactive elements on the page




### Links


- Solution URL: (https://suryagumilar.github.io/fylo-landing-page/)


### My process
1. Look through the designs to start planning out how to tackle the project. This step is crucial to help me
 think ahead for CSS classes to create reusable styles.

2. Structure the content with HTML. Writing HTML first can help focus 
 my attention on creating well-structured content.

3. Write out the base styles, including general content styles, such as `font-family` 
 and `font-size`.

4. Start adding styles to the top of the page and work down. Only move on to the next section 
 once i am happy i've completed the area i am working on.


### Built with


- Semantic HTML5 markup

- CSS custom properties

- Flexbox

- CSS Grid

- Mobile-first workflow


### What I learned
```html

<!-- to add icon -->
	<link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
```

```css
/* fit images with screen size */
	.imgbox {
	display: grid;
	height: 100%;
	}

	.center-img {
	max-width: 100%;
	max-height: 100vh;
	margin: auto;
	}

/* change color of image to black or white */
	#white-logo {
	-webkit-filter: brightness(0) invert(1);
	filter: brightness(0) invert(1);
	}
```




### Continued development

Change color of images when hover.



### Author


- Blog - [Surya Gumilar](wriette.blogspot.com)

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/SuryaGumilar)
