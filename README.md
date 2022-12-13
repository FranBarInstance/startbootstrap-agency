# [Editor for template content](https://github.com/TheNocoder/ncSimpleHtmlEditor)

Allows you to edit the content of previously created templates or designs, it does not have options to change the design.

## Preview

![agency](https://user-images.githubusercontent.com/114579121/193446865-ef500949-f3f9-4374-9c27-32d2fb7d43f5.gif)

## Demo

https://thenocoder.github.io/ncSimpleHtmlEditor/demo/grayscale/

## Basic Usage

Download your template from here https://startbootstrap.com/theme/agency or any other from here: https://github.com/StartBootstrap

Add this code at the end of index.html, immediately before /body:

```html
<!-- ncsedt-implement:before -->
<div id="ncsedt-implement">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/TheNocoder/ncSimpleHtmlEditor@master/ncsimplehtmleditor.css">
    <script src="https://cdn.jsdelivr.net/gh/TheNocoder/ncSimpleHtmlEditor@master/ncsimplehtmleditor.js"></script>
    <script>
        var editor = new ncSimpleHtmlEditor();
        editor.start();
    </script>
</div>
```

When you finish editing your template click on save, you get an index.html file that you must replace with the one you downloaded with the template.

And that's it!

## Advanced Usage

Go: https://github.com/TheNocoder/ncSimpleHtmlEditor

## Copyright and License

MIT license
