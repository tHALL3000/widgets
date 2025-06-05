# Widget Development Guide

## Creating a New Widget

1. Create HTML file in `widgets/` folder
2. Use this template structure in `index.html`:

```html
<div class="widget">
    <div class="widget__header">
        <div class="widget__title">Widget Name</div>
        <div class="widget__description">Brief description</div>
    </div>
    <iframe src="widgets/your-widget.html" class="widget__frame" height="300"></iframe>
</div>
```



### 4. **Save the main HTML file:**
- Copy the HTML from our artifact
- Save as `index.html` in the root folder

### 5. **Optional: Extract CSS to separate file:**
If you want to keep CSS separate, create `styles/main.css` and move the CSS there, then link it in `index.html`:

```html
<link rel="stylesheet" href="styles/main.css">