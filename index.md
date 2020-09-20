# Guides

[Imporve this page](https://github.com/Brunozhon/guides/edit/gh-pages/index.md)

<hr>

## Starting a HTML file

a. Create a repo named `demo_repo` (or whatever you like)

b. Create a file named `index.html` and put this content in:
```html
<html>
  <head><title>Hello world!</title><meta name="viewport" content="width=device-width, initial-scale=1.0" /></head>
  <body>
    <h1>Hello world!</h1>
    <hr />
    <p>This is a paragraph.</p>
  </body>
</html>
```
c. Click "Commit changes".

d. DONE!

## Creating a CSS file

a. Create a file named `style.css`

b. Add:
```css
* {
  display: block;
}
body, html, head {
  magrin: 0px;
  padding: 0px;
  width: 100%;
}
.one-fourth {
  display: inline-block;
  width: 25%;
}
.one-half {
  display: inline-block;
  width: 50%;
}
.three-fourth {
  display: inline-block;
  width: 50%;
}
.whole {
  display: block;
  width: 100%;
}
a:link, a:hover, a:active, a:visited {
  color: #000000;
}
```
c. Click commit changes and add `<link rel="stylesheet" href="style.css" />` to the head element. It should look like:
```html
<html>
  <head>
    <title>Hello world!</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Hello world!</h1>
    <hr />
    <p>This is a paragraph.</p>
  </body>
</html>
```
d. Adding rules:

   A. If you put `style.css` in a folder, the attribute href of the link element should look like *`folder/path/to/file/`*`style.css`. **Be sure to escape any non ASCII charecters, such as " " (space) to %20, like `CSS%20styles/style.css`**.
   
   B. If you put `style.css` in the root, add a slash, like `/style.css`.
   
   C. If you want a absolute link, such as https://brunozhon.github.io/index.html, add *`protocol://pre-domain.domain.extension/foldername/`*`style.css`
   
e. Click "Commit changes"
