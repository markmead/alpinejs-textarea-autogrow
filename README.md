# Alpine JS Textarea Grow

Alpine JS plugin `x-grow` adds in auto grow functionality to `<textarea>` elements 🌳

## Example 👀

```html
<textarea x-data x-grow></textarea>
```

This `<textarea>` will now grow with the content.

## Install 🌟

It's very easy to install Alpine JS plugins! 🙌

### CDN

```html
<script src="https://unpkg.com/alpinejs-textarea-grow@1.0.0/dist/grow.min.js"></script>
<script defer src="https://unpkg.com/alpinejs@3.x.x/dist/cdn.min.js"></script>
```

### NPM/Yarn

```shell
npm i -D alpinejs-textarea-grow

yarn add -D alpinejs-textarea-grow
```

Then you can register the plugin.

```js
import Alpine from "alpinejs";
import grow from "alpinejs-textarea-grow";

Alpine.plugin(grow);

window.Alpine = Alpine;

Alpine.start();
```

### Stats 📊

Here's some stats about the Alpine JS Textarea Grow package! As you can see, it's tiny 🤏

![](https://img.shields.io/bundlephobia/min/alpinejs-textarea-grow)
![](https://img.shields.io/npm/v/alpinejs-textarea-grow)
![](https://img.shields.io/npm/dt/alpinejs-textarea-grow)
![](https://img.shields.io/github/license/markmead/alpinejs-textarea-grow)
