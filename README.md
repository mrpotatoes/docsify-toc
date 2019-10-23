# Docsify Table of Contents

<p align="center">
  <img src="https://docsify.js.org/_media/icon.svg" />
  <br />
  <code>docsify-toc</code>
</p>


**Note**: I won't be adding features but feel free to add pull requests and if they work/pass tests I'll add them in.

## To use
Add stylesheet
```html
<link rel="stylesheet" href="https://unpkg.com/docsify-toc@1.0.0/dist/toc.css">
```

Add JS
```html
<script src="https://unpkg.com/docsify-toc@1.0.0/dist/toc.js"></script>
```

Add settings
```js
window.$docsify = {
  toc: {
    scope: '.markdown-section',
    headings: 'h1, h2, h3, h4, h5, h6',
    title: 'Table of Contents',
  },
}
```

# TODO
- [ ] Tests
- [ ] Example
- [x] ~Documentation~
