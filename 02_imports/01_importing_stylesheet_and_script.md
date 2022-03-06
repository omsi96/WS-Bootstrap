# Imports
Let’s start by creating our `index.html` and filling it with the template using the `!` emmet shortcut.
<br/>
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
Make sure you start the live server. Now let’s import the stylesheet from `node_modules/bootstrap/dist/css`.
<br/>
![css import](https://user-images.githubusercontent.com/18662979/155153308-d196441d-1363-4dbb-a248-42eb02146a0d.png)

<br/>
If we scroll all the way to the bottom, we will find `bootstrap.css`
<br/>
For the script, we will do the same using the script tag. The defer attribute will ensure the JavaScript file is downloaded and ready by the time the DOM is done rendering.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.css">
    <script defer src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
    <title>Document</title>
</head>
```
We are now ready to use Bootstrap! 🎉
<br/>
