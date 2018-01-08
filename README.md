# system-ui.css

An opinionated system-ui fallback, exposed as a class

### Why

I needed a targeted way to experiment with a system-font.

### What

Here's all the code.

```css
.system-ui {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}
```

### Usage

The package exposes the class `system-ui`.

#### browser

```html
<link rel="stylesheet" href="https://unpkg.com/system-ui.css" />
```

#### webpack

```bash
npm i -P system-ui.css

# or

yarn add system-ui.css
```

```js
import "system-ui.css";
```

### License

&copy; 2018 John Doe All Rights Reserved

MIT
