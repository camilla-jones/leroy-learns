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

This is the code for a very basic webpage. This made using HTML(Hyper Text Markup Language).

HTML documents are made up of tags e.g `<h1>`.They are used to tell the browe how to render the information. Most tags usualy have an ending tag in the format of `</h1>` denoting the end of the element however there are a lot of excetions to the rule so refer to documention of in doubt. Tags not case sentive however it is best pratice to use lower case.

The HTML document starts with `<!DOCTYPE html>` This tells the web brower that this is a HTML document. Not depfifieing the version meand that the browe defaults to html5 (most recent).

The `<html>` tags tell the borwers that in between these tow tages there is htmnl for the brower to render. As can been seen the example this ends with the closinjg tag `</html>`

The next section of the html document in the `<head>`. The `<head>` section stores the metadata of the website. For example, title of the page and CSS code (more on that later)

The main section of the HTML doucment is the body. The body is what the user see when looking at the web page.the tags `<body>` wrap around the visable content of the website. Inside this example the `<body>` has a heading and paragraph ( `<h1>`and`<p>`). The ending simaily to the other tags denotes the end of th body

## Main Takeaways of lesson

### Key points

- All HTML doucments have to start with `<!DOCTYPE html>`
- Page metadata is stored in the head tags
-page elements are sotred in the `<body>`
- endtage tell the browser when one element ends and when the next one beginngs 

### Tags used

`<!DOCTYPE html>`
: Denotes begging of html document

`<html>`
: tag used to signify html

`<head>`
: demotes header of page

`<body>`
: Doamte main body of html docums. Put stuff you want the user to see between these two tags.

`<h1>`
: tag for headers. Goes from 1 to 6 with 1 being the lagrest and 6 being the smallest

`<p>`:
demotes a paragraph