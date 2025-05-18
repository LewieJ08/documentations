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

<hr>
<br>

```html
<html> </html>
```

These are HTML tags. These are again, within every HTML file. These tags indicate to the brower that all the code between these tags are HTML showing the start and endpoint of the code. These should be at the top and bottom of the file under the ```<!DOCTYPE html>``` tag.

<hr>
<br>

```html
<head> </head>
```

These are Head tags, they define the <b>Head</b> section of the HTML. The <b>Head</b> section contains meta data about the page like the title, favicon or styling link (all things that will be mentions within this doc).

<hr>
<br>

```html
<head>
    <title>My first website</title>
</head>
```

This is an example of what you would use inside of the head tags. These are title tags which are used to determine the <b>Title</b> of the webpage. the title can be seen within the browser like this:

 ![title shown in browser](/images/title_tag.png)

<hr>
<br>

 ```html
<body> </body>
 ```

Along with the head section of our HTML we also have the <b>Body</b>. This is where all of the main elements are, the ones that are <b>displayed</b> on the webpage.

<hr>
<br>

```html
<body>
    <h1>this is a h1 heading</h1>
    <h2>this is a h2 heading</h2>
    <h3>this is a h3 heading</h3>
    <h4>this is a h4 heading</h4>
    <h5>this is a h5 heading</h5>
    <h6>this is a h6 heading</h6>
</body>
```

These are <b>Heading</b> tags. there are 6 different sizes, the larger the number, the smaller the heading. as these are elemenst that are used within the <b>Body</b> they will be displayed on the webpage.

This is the output of these Heading tags:

![image of headings](/images/headings.png)

As you can see the sizing is different depending on the number used within the heading tag as mentioned before.

<hr>
<br>
