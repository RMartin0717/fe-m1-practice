# HTML and CSS: Design and Build Websites

## Chapters 3 and 4 on Lists and Links

### There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
- Ordered lists number each item, unordered lists include a bullet point before each item, and definition lists show sets of terms along with definitions for each item.

### What is the basic structure of an element used to link to another website?
- links are created using ```<a>``` element, href specifies the linked page, and the link that the user sees goes in between the ```<a>``` elements.
ex:```<a href="http://www.link.com">Link</a> ```

### What attribute should you include in a link to open a new tab when the link is clicked?
- target
### How do you link to a specific part of the same page?
- Use the id attribute to identify points in the page that a link can go to, then link to that section using # before the id name.
ex:
```
<h1 id="top">Title</h1>
...
...
<p><a href="#top">Top</a></p>
```

## Chapters 10, 11, and 12 on What is CSS, Color and Text

### What is the purpose of CSS?
- To stylize web pages

### What does CSS stand for? What does cascading mean in this case?
- Cascading Style Sheets

### What is the basic structure of a CSS rule?
- A CSS rule includes a selector which indicates which element the rule applies to and declarations, which indicate style

### How do you link a CSS stylesheet to your HTML document?
- In the head element, use ```<link>``` and include href to specify the CSS file path, type to specific the type of doc that is being linked (text/css), and rel to specify the relationship between the HTML page and the file it is linked to (stylesheet)

### When is it useful to use external stylesheets as opposed to using interal CSS?
- External stylesheets are useful for any website containing multiple pages, but can be used even if there is only one page. This is so that changes to the code affect each page without having to go edit every page. It can be helpful to use internal CSS when there is only one web page, but you can still use external stylesheets then too.

### Describe what a color hex code is.
- HEX codes are 6 digit codes that use hexidecimal/base 16 characters (digits 0-9, a-f) to assign color in a declararion; ex: ee3e80

### What are the three parts of an HSL color property?
- Hue, Saturation, Lightness

### In the world of typeface, what are the three main categories of fonts? What are the differences between them?
- serif (has extra details at ends of main strokes), sans-serif (straight ends), monospace (each letter is same width)

### When specifiying font-size, what are the main three units used?
- pixels, ems, percentage
