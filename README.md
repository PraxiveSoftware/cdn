# cdn
📦 public repository including static files used by the praxive browser environment

## 🎯 Endpoints
### `GET /static/img/<file>`
> Returns the image file requested.
### `GET /static/svg/<file>`
> Returns the svg file requested.

----

## 🛠️ Usage
### Image 🖼️
```html
<img src="https://cdn.praxive.io/static/img/<file>" alt="Image">
```
### SVG 📄
```html
<object type="image/svg+xml" data="https://cdn.praxive.io/static/svg/<file>"></object>
```
### CSS 🎨
```css
body {
  background-image: url('https://cdn.praxive.io/static/img/<file>');
}
```
### JavaScript 📜
```javascript
const img = new Image();
img.src = 'https://cdn.praxive.io/static/img/<file>';
```
### Markdown 📝
```markdown
![Image](https://cdn.praxive.io/static/img/<file>)
```

## 🤝 Contributing
> Feel free to contribute to this project by providing new useful svg or image files. You can do this by creating a pull request with the new files added to the `static/img` or `static/svg` directories which then will be reviewed and possibly merged.

## 📄 License
This project is licensed under the Apache-2.0 License - see the [LICENSE](https://github.com/PraxiveSoftware/cdn/blob/main/LICENSE) file for details.
```

[]: # Path: LICENSE
```