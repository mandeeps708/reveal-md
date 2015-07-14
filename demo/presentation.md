# Markdown Revealed

Note: Presentation using reveal-md

----

#Reveal-md

----

#Reveal.js + Markdown

---

<section data-background-transition="slide" data-markdown style="background-color: rgba(255,255,255,0.1);"><h1>What is Reveal.js?</h1></section>

----

> [Reveal.js](https://github.com/hakimel/reveal.js) is a framework for creating beautiful presentations using web technologies.

---

#Markdown

----

>[Markdown](https://guides.github.com/features/mastering-markdown/) is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.

---
<!--
<section data-background-video="avengers.mp4">
....
</section>

--- -->

##Fragments

---

<section data-background="#EEE">
    <p class="fragment grow">grow</p>
    <p class="fragment shrink">shrink</p>
    <p class="fragment fade-out">fade-out</p>
    <p class="fragment current-visible">visible only once</p>
    <p class="fragment highlight-current-blue">blue only once</p>
    <p class="fragment highlight-red">highlight-red</p>
    <p class="fragment highlight-green">highlight-green</p>
    <p class="fragment highlight-blue">highlight-blue</p>
</section>

---

## Fragment Code
```html
<section data-background="#EEE">
    <p class="fragment grow">grow</p>
    <p class="fragment shrink">shrink</p>
    <p class="fragment fade-out">fade-out</p>
    <p class="fragment current-visible">visible only once</p>
    <p class="fragment highlight-current-blue">blue only once</p>
    <p class="fragment highlight-red">highlight-red</p>
    <p class="fragment highlight-green">highlight-green</p>
    <p class="fragment highlight-blue">highlight-blue</p>
</section>
```

---

And if you'd like to use syntax highlighting, include the language:

<pre>```javascript
if (isAwesome){
  return true
}
```
</pre>


####Output:

```javascript
if (isAwesome){
  return true
}
```

---

<section data-transition="zoom" data-background="#FE642E" backgroundTransition: "slide">
Background Slides
</section>

---

<section data-background="#01DFD7" data-background-transition="convex" data-transition="fade">
Changing Background Transitions
</section>

---

<section data-background="#EEE" data-background-transition="concave" data-transition="fade">
Again
</section>

---

<section data-background-transition="zoom" data-background="#0074D9">
<!-- .slide: data-background="#ff00ff" -->
zoom background</section>

---

<section data-background-transition="zoom" data-background="#2ECC40">
OK.
</section>

---

#Modifying defaults

---

###reveal.json

```
{
	"controls": false,
	"progress": true, 
	"transition": "zoom",
	"backgroundTransition": "slide",

    // Parallax background image
	"parallaxBackgroundImage": "sea.jpg",

	"parallaxBackgroundSize": "2100px 900px",

	// Amount of pixels to move the parallax background per slide step,
    // a value of 0 disables movement along the given axis
    // These are optional, if they aren't specified they'll be calculated automatically

	"parallaxBackgroundHorizontal": 1000,
    "parallaxBackgroundVertical": 50
	
}
```

---

#Installation

<section data-background="#04B486" data-markdown>

https://github.com/webpro/reveal-md/</p>

<br>
npm install -g reveal-md

</section>

Note: You may need to install nodejs

---

---

#Changing themes

reveal-md slides.md --theme solarized


```css
The framework comes with a few different themes included:

    black: Black background, white text, blue links (default theme)
    white: White background, black text, blue links
    league: Gray background, white text, blue links (default theme for reveal.js < 3.0.0)
    beige: Beige background, dark text, brown links
    sky: Blue background, thin dark text, blue links
    night: Black background, thick white text, orange links
    serif: Cappuccino background, gray text, brown links
    simple: White background, black text, blue links
    solarized: Cream-colored background, dark green text, blue links
```

---

#The End.
