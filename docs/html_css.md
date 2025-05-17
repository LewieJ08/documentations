# HTML - CSS Documentation

### (HyperText Markup Language) - (Cascading Style Sheets)


## Intro
HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements"

A HTML element is set off from other text in a document by "tags", which consist of the element name surrounded by ```<``` and ```>```. The name of an element inside a tag is case-insensitive. That is, it can be written in uppercase, lowercase, or a mixture. For example, the ```<title>``` tag can be written as ```<Title>```, ```<TITLE>```, or in any other way. However, the convention and recommended practice is to write tags in lowercase.

## Basic HTML 

```html
<!DOCTYPE html>
```

This HTML tag is used at the start of every HTML file. It is a way to tell the brower that this is HTML and tells it how to render the page correctly.

```html
<html> </html>
```

These are HTML tags. These are again, within every HTML file. These tags indicate to the brower that all the code between these tags are HTML showing the start and endpoint of the code. These should be at the top and bottom of the file under the ```<!DOCTYPE html>``` tag.

```html
<head> </head>
```

These are Head tags, they define the header section of the HTML. The header section contains meta data about the page like the title, favicon or styling link (all things that will be mentions within this doc).

```html
<head>
    <title>My first website</title>
</head>
```

This is an example of what you would use inside of the header tags. These are title tags which are used to determine the title of the webpage. the title can be seen within the browser like this:

