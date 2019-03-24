# Morning Coffee: Programming as an art form

### A website built using [GitHub Pages](https://pages.github.com/), which can be viewed at [morningcoffee.life](http://morningcoffee/life).

During my last year at university, our Digital Document Design professor assigned to his students a 5-page, static website, using HTML5 and CSS3. The subject matter could be anything we liked, so long as we provided general information, links to commentary on the subject from other sources, embedded video, and a gallery of images. 

I chose coffee, part of a beloved morning ritual. 

Aside from classwork on markup languages, I have semi-regular programming sessions with John, a friend and mentor in the industry. 

John believes that programming is an art form. Written with care and cleverness, code offers layers of meaning to uncover and enjoy. To this end, I created not only a website about coffee, but with naming conventions and comments that reflected not only the function of each class and id, but described the experience of savoring a cup of freshly ground coffee in the company of a fuzzy feline.

For example, in HTML, the `<div>` that marks each page footer is named `aftertaste`, to conjure an image of flavor notes that linger after the body of the experience. The wrapper is named `ritual`, indicating that the entire project is wrapped in the comforts and rhythms of the dance of waking up. Accessibility is important, so I included alternate text on the images for screen readers.

The HTML files are meant to be read a bit like a book. Each has a commented “chapter” between the head and the body. For example, in `roast.html`, it reads as follows:

```
</head>

<!-------------
-- CHAPTER 2 --  taste the rainbow
-------------->

<body class="thatbeautifulbean">
	<div id="ritual">
```
The CSS file is also organized by “chapter,” with unique styling for each web page.

```
/* * * * * * * *
 *             *
 *  ROASTED!   *
 *             *
 * * * * * * * */

body.thatbeautifulbean {
	background-color:#4f4359;
	font-family: 'Neucha', cursive;
	font-size: 2.4rem;
	color: #e0e0d5;
}
```
For added fun, the background image of the final page is colored in the hex code `#C0FFEE`.

Visually, each page represents a stage of wakefulness, from a dark color scheme, messy font, and rounded images at the landing page to a crisp, lively gallery of coffee memes with vibrant colors, precise letters, and sharp corners. All header images are my original sketches. 


Enjoy, friends, passers-by, and fellow coffee lovers.
