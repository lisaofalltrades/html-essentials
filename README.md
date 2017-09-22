# HTML ESSENTIALS

## Resources
- [W3Cs HTML](https://www.w3.org/html)
- [HTML - Living Standard](https://html.spec.whatwg.org/multipage/)
- [Web Platform](https://webplatform.github.io/docs/html/)
- [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML)

## Basic Page Structure
```html
<!DOCTYPE HTML>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="description" content="A page for exploring basic HTML documents">
        <title>Basic HTML Document</title>
    </head>
    <body>
        <h1>Page Content</h1>
        <p> The main page content appears inside the <body>body</body> tag. HTML contains several elements tahta llow you to properly structure and format your content, which we'll cover later.</p>
    </body>
</html>
```
### DOCTYPE declarations
```html
<!DOCTYPE HTML>
```
- Triggers something called quirks mode. Makes sure your webpage is rendered in the right format

### The Document head
```html
<html lang="en">
</html>
```
- Not required but nice to set the language
- Useful for screen readers in terms of how they enunciate the text as well as online translators

```html
<head>
    <meta charset="utf-8">
</head>
```
- uses proper characters when rendering the page

```html
<head>
    <meta name="description" content="A page for exploring basic HTML documents">
</head>
```
- brief summary of the page
- used for search engines on the results page

```html
<head>
    <title>Basic HTML Document</title>
</head>
```
- Unprofessional without online
- shows up in search results & on the browser tab

### The Document body
```html
<body>
</body>
```
- sibling of head tag
- the body tag is necessary for us to have any visible content whatsoever
- the body element represents the visual elements on the page

### Understanding content models
- almost every element in HTML belongs to a content models
- these define the type of content expected inside an element and control syntax rules such as element nesting

Prior to HTML5, there were two models
- **Block Level Elements** take up their own line within the flow of the docment.
- **Inline Level Elements** basically appear within the flow of other content.

[Updates in HTML5](https://www.w3.org/TR/2011/WD-html5-20110525/content-models.html#kinds-of-content)
Content models now include flow, metadata, embedded, interactive, heading, phrasing, and sectioning

**Metadata**
This is content that's  defined as setting up the presentation or the behavior of the rest of the content. You will pimarily find these elements in the head of the document. And it's going to contain things like metatags, no-script tags, script tags, style tags, the title tag of pages, etc.


Embedded

```html
<body>
</body>
```

## Formatting Page Content
```html
<pre>Typically used with coding examples.</pre>
```
### Using Headings
```html
<h1>H1</h1>
<h2>H2</h2>
<h3>H3</h3>
<h4>H4</h4>
<h5>H5</h5>
<h6>H6</h6>
```
- Prior to HTML5, the only sectioning elements that we had for our page were headers.
- Used to create and rank sections within our page.
- Can use multiple H1 headers to a page
- Don't skip a series of headings. For example, you don't want to go from H1 to H5.

### Formatting Paragraphs
- if you don't wrap text in an element, most browsers are going to default the formatting like a paragraph

### Controlling line breaks
