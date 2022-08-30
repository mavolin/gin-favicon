# gin-favicon
Generate a favicon from a single file at runtime.

Add this to your head and replace `PREFIX` with the path prefix, or remove it if you serve your favicons at root.

```html
<link rel="apple-touch-icon" sizes="180x180" href="PREFIX/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="48x48" href="PREFIX/favicon.png">
<link rel="icon" type="image/png" sizes="32x32" href="PREFIX/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="PREFIX/favicon-16x16.png">
<link rel="manifest" href="PREFIX/site.webmanifest">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff">
```
