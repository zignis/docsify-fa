Inspired from [erickjx/docsify-fontawesome](https://github.com/erickjx/docsify-fontawesome), allows you to apply custom colors to the icons.
# ⚙️ Setup
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
<script src="https://cdn.jsdelivr.net/gh/zignis/docsify-fa/script.min.js"></script>
```
# :hammer: Usage
The syntax is `:fa(style) fa-(icon_name) ...:[c=(color_resolvable)]`, the color parameter is optional.
Text enclosed by `:fa :` will be parsed to CSS, for example:
```
:fas fa-cog:[c=#fff]
``` 
will be parsed to 
```html
<i style="color:#fff;" class="fas fa-cog"></i>
```
Any of the following styles can be used: 
- `:fas fa-cog:`
- `:fas fa-cog:[c=black]`
- `:fad fa-cat:[c=#FFFFFF]`
- `:fas fa-pencil:[c=blue]`
- `:fas fa-aws:[c=hsla(120,100%,25%,0.3)]`
- `:fas fa-home:[c=rgb(0,0,255)]`.

Basically anything that works in CSS should work here.
# :link: Links
- [Font Awesome](https://fontawesome.com/)
- [Docsify](https://docsify.js.org/#/)
- [erickjx/docsify-fontawesome](https://github.com/erickjx/docsify-fontawesome)

# :ledger: License
[Apache License 2.0](https://github.com/zignis/docsify-fa/blob/main/LICENSE)

