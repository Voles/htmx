---
layout: layout.njk
title: </> htmx - high power tools for html
---

## The `remove-me` Extension

The `remove-me` extension allows you to remove an element after a specified interval.

### Install

```html
<script src="https://unpkg.com/htmx.org/dist/ext/remove-me.js">
```

### Usage

```html
<div hx-ext="remove-me">
    <!-- Removes this div after 1 second -->
    <div remove-me="1s">To Be Removed...</div>
</div>
```
