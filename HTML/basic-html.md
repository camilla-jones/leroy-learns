---
layout: page
title: First Lesson Creating your First web page!
---
# Basic HTML

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<!--This is a comment. Comments are not displayed in the browser-->
<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## Description of HTML

This is the code for a very basic webpage. This is made using HTML(Hyper Text Markup Language).

HTML documents are made up of tags e.g `<h1>`.They are used to tell the browe how to render the information. Most tags usually have an ending tag in the format of `</h1>` denoting the end of the element however there are a lot of exceptions to the rule so refer to documentation if in doubt. Tags are not case sensitive, however it is best practice to use lower case. American English spelling is used, for example `color` not `colour`

The HTML document starts with `<!DOCTYPE html>` This tells the web browser that this is a HTML document. Not identifying the version means that the browser defaults to html5 (most recent).

The `<html>` tags tell the browser that in between these two tags there is html for the browser to render. As can been seen the example this ends with the closing tag `</html>`

The next section of the html document in the `<head>`. The `<head>` section stores the metadata of the website. For example, title of the page and CSS code (more on that later)

The main section of the HTML document is the body. The body is what the user sees when looking at the web page.the tags `<body>` wrap around the visible content of the website. Inside this example the `<body>` has a heading and paragraph (`<h1>`and`<p>`). The ending simaily to the other tags denotes the end of the body

## Main Takeaways of lesson

### Key points

- All HTML documents have to start with `<!DOCTYPE html>`
- Page metadata is stored in the `<head>` tags
- Page elements are sotred in the `<body>`
- Tags can also affect how content is rendered in the browser
- Tags are defined as either opening `<x>` or closing `</x>`

### Tags used

`<!DOCTYPE html>`
: Denotes begging of html document

`<html>`
: Tag used to signify html

`<head>`
: Denotes header of page

`<body>`
: Denotes the main body of html docums. Put stuff you want the user to see between these two tags.

`<h1>`
: Tag for headers. Goes from 1 to 6 with 1 being the lagrest and 6 being the smallest

`<p>`:
Dnotes a paragraph
