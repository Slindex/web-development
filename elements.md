# General Elements

This section covers the most general and used structural elements of the HTML language.

## DOCTYPE

This element determines the rules for **rendering** the HTML language. It is used usually at the beggining of any `html` file as follows:

```html
<!DOCTYPE html>
```

## HTML

This element wraps all the content on the page. It is known as the root element:

```html
<html lang="en-US">
```

## Head

The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page `<title>`, links to CSS (if you choose to style your HTML content with CSS), links to custom favicons, and other metadata (data about the HTML, such as the author, and important keywords that describe the document).

```html
<head>
    <meta charset="utf-8" />
    <title>My test page</title>
</head>
```

## Title

Contains the page title showed in the browser tab:

<p align='center'>
    <img src='src/title.png' />
</p>

Markdown syntax is as follows:

```html
<title>My test page</title>
```

## Body

This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.

```html
<body>
    <h1>Content</h1>
</body>
```

# Common Tags

## h1

Used for define a document title.

```html
<h1>Doc title</h1>
```

## p

Used for define a paragraph.

```html
<p>Paragraph</p>
```

## img

Used for embed an image in the document content. There are 4 important properties for embedding images:

* **src**: link or local path to image
* **alt**: image title or description
* **height**: image height in pixels
* **width**: image width in pixels

```html
<img src="https://exampleimage.com" alt="image description" height=400 width=400 />
```

## anchor

Used for embed links in the document content. The `href` property is used in this tag to save the final URL.

```html
<a href="https://www.example.com">Text with Redirection</a>
```

## span

Used for applying css or javascript to a specific element without giving any extra meaning.

```html
<span style="font-size: 32px; margin: 21px 0; display: block;">
  Is this a top level heading?
</span>
```

# Entity References

| Literal Character  | Reference |
| :----------------: | :-------: |
| <                  | `&lt;`    |
| >                  | `&gt;`    |
| "                  | `&quot;`  |
| '                  | `&apos;`  |
| &                  | `&amp;`   |

# Important Links

* [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
* [Google's WebMaster Tool](https://search.google.com/search-console/about?hl=en)