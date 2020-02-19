# Typography style set
CSS style sheet, that optimizes a blog posts
### *Index.html* serves as an example of use
## Implementation

```html
<!DOCTYPE html>
<html lang="cs">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Blog typography</title>
    <!-- link Monserrat font from google fonts first -->
    <link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
    <!-- load stylesheet (main.css) second -->
    <link rel="stylesheet" href="main.css" />
  </head>
</html>
```
## Usage
This style sheet is based on a *html* structure, so you just need to change atributes in *index.html*

Entire blog is basically closed in <article> tag.

```html
<article>
      <p>
        Lorem ipsum...
      </p>
      <h1>H1 - First heading</h1>
      <p>
        Lorem ipsum...
      </p>
</article>
```

## Components
### Header 
```html
<header>
     <h2>Blog Typography set</h2>
     <div>11. 02. 2020 16:25:35 </div>
</header>
```

### Buttons
```html
<button>Click Here</button>
```

### Image with caption
```html
<figure>
    <img src=" "  alt=" "/>
    <figcaption>
        Photo by <a href=" ">Name of author</a>
    </figcaption>
</figure>
```

### Lists
```html
<ol> <!-- or <ul> instead of <ol> -->
    <li>Category One</li>
    <li> Category Two
        <ol>
        <li>Sub-category</li>
        <li>Sub-category</li>
        </ol>
    </li>
    <li>Category Three</li>
</ol> 
```

### Blockquote
```html
<blockquote cite=" "> Lorem ipsum </blockquote>
```

### Footer 
```html
<footer>
    <div>
        <b>Author: xxx</b> | date and time | readed: x
    </div>
</footer>
```
