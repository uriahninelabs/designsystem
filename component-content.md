---
layout: docs
title: Content Sections // Components
---

# Content Containers


## Article Summary

Article Summaries extend the [Bootstrap Card Component](https://getbootstrap.com/docs/4.4/components/card/) and are intended to be used whenever you want to provide a brief preview of an article (e.g. the Home Page, the Blog Archive, etc.)

{% include _component-blog-article-preview.html %}

```html
{% include _component-blog-article-preview.html %}
```


## Topic Containers

This component is meant to be used to provide an overview of a service area or outcome. The text should be limited to about 90 words in no more than three paragraphs. When multiple Topic Containers are used together on a page you should alternate between the default `.topic-container` and `.topic-container-right` so the images will alternate between the left and right side.

### Image Left

{% include _component-topic-container.html %}

```html
{% include _component-topic-container.html %}
```

----

### Image Right

{% include _component-topic-container-right.html %}

```html
{% include _component-topic-container-right.html %}
```

----
