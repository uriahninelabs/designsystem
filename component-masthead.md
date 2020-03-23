---
layout: docs
title: Mastheads // Components
---

# Mastheads

A Masthead is a full-width component used at the top of first-level pages.

## Image Masthead

The Image Masthead includes a background image which is set using an inline `style="background-image:url(...)"` declaration. It includes a `H1` level Heading, a paragraph of text, and an optional Call-to-Action button.

{% include _component-masthead-image.html %}

```html
{% include _component-masthead-image.html %}
```

----

## Default Masthead

The default Masthead includes a `H1` level Heading, a paragraph of text, and an optional Call-to-Action button.

{% include _component-masthead.html %}

```html
{% include _component-masthead.html %}
```

----

## Simple Masthead

The default Masthead includes a `H1` level Heading and a paragraph of text, but does not have any call-to-action.

{% include _component-masthead-simple.html %}

```html
{% include _component-masthead-simple.html %}
```

----

## Article Masthead

For blog articles and white-papers. You'll see it is very similar to the simple masthead, but replaces the paragraph of text with information about the article or white-paper.


{% include _component-masthead-article.html %}

```html
{% include _component-masthead-article.html %}
```
