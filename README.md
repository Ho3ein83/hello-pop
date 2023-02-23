# Hello popup
Hello popup is a user interface component & script that can display alert messages and toasts to users and handle popup interactions. You can add custom buttons, timeout, forms, icons, etc.

## Installation
jQuery is required for this module, that means you have to load jQuery before module **(jQuery 3.2.1 or higher is recommended)**, then link module stylesheet and script:

```html
<!-- jQuery -->
<script src="jquery.js"></script>

<!-- Hello module -->
<link rel="stylesheet" href="hello.css">
<script src="hello.js"></script>
```

### How to use
Simple alert
```javascript
Hello.fire({
    title: "Hello world!",
    text: "Popups are awesome!"
});
```

Toast box
```javascript
Hello.fire({
    text: "Hey there 👋",
    type: "toast",
    position: "mm", // Middle Middle
    timeout: 3000   // 3 seconds
});
```

### More
For more information about this module and more examples download this project and open index.html file.
