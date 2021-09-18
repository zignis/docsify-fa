Inspired from [erickjx/docsify-fontawesome](https://github.com/erickjx/docsify-fontawesome)
# Setup
Inject FontAwesome CSS files to your main html file:
```html
<!-- index.html -->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/fontawesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/brands.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/regular.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/solid.min.css">

<!-- OR Inject all the icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
```

Inject the script in the same document:
```html
<script src="_"></script>
```
# Usage
The syntax is `:fa(style) fa-(icon_name) ...:[c=(color_resolvable)]`, the color parameter is optional.
Text enclosed by `:fa :` will be parsed to CSS, for example:
```
:fas fa-cog:[c=#fff]
``` 
will be parsed to 
```html
<i style="color:#fff;" class="fas fa-cog"></i>
```
Any of the following styles can be used: `:fas fa-cog:`, `:fas fa-cog:[c=black]`, `:fad fa-cat:[c=#FFFFFF]`, `:fas fa-pencil:[c=blue]`.

# Links
[Font Awesome](https://fontawesome.com/) | [Docsify](https://docsify.js.org/#/)

# License
[Apache License 2.0](https://github.com/HexM7/docsify-fa/LICENSE)

