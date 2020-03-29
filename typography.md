---
layout: docs
title: Typography
---

# Typography

Approved fonts and type styles for usage in Nine Labs digital products.

----

## Headings

Headings use <a href="https://fonts.google.com/specimen/Fira+Sans">Fira Sans</a> and range from *72px* for `h1` to *18px* for `h6`. Note that the `h4` and `h5` headings are the same *font-size*, but different styles. The `h4` heading is set to uppercase using `text-transform: uppercase` and is set to be the Brand Pink color, while the `h5` heading follows the pattern and style from the other headings. This is so we can easily create the emphasis we want in various circumstances.

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>


```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
----

### Typical Page Heading

<div class="container">
  <div class="row">
    <div class="col my-5">
      <div class="highlight-bar"></div>
      <h1>This is the headline</h1>
      <p>This is an optional line of text that compliments the heading.</p>
    </div>
  </div>
</div>

```html
<div class="container">
  <div class="row">
    <div class="col my-5">
      <div class="highlight-bar"></div>
      <h1>This is the headline</h1>
      <p>This is an optional line of text that compliments the heading.</p>
    </div>
  </div>
</div>
```



### The Highlight Bar

When headings `h1`, `h2`, or `h3` are used at the top of a page or the beginning of a new section of content you should include the Highlight Bar above the `hx` element. The bar automatically resizes to 18% of the heading's container width, with a minimum width of 90px.

*Note: The Highlight Bar is not to be used with `h4`, `h5`, or `h6` level headings.*

<div class="highlight-bar"></div>
<h2>This is the Title of a Content Section</h2>

```html
<div class="highlight-bar"></div>
<h2>This is a Title</h2>
```

----

## Body Copy

All other text is set in <a href="https://fonts.google.com/specimen/Merriweather">Merriweather</a> at *18px* with a `line-height` of *1.5rem*.

----
### Paragraphs

Every day is taco ipsum tuesday. Carne asada on corn tortillas. Give me all the tacos, immediately. Flour or corn tortillas? Shrimp tacos are tasty tacos! BARBACOA!! It’s a wonderful morning for breakfast tacos. Can you put some peppers and onions on that? Josh’s taco shack is the best taco shack. CARNE ASADA!! Um, Tabasco? No thanks, do you have any Cholula? How bout a gosh darn quesadilla? It’s taco Tuesday Monday. Josh’s taco shack is the best taco shack. Does guac cost extra? Pico de gallo, on the side please

----
### Lists

- Tacos
- Burritos
- Nachos
- Chips &amp; Salsa
- Guacamole!
