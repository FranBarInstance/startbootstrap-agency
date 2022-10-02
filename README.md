# [Editor for template content](https://github.com/TheNocoder/ncSimpleHtmlEditor)

Allows you to edit the content of previously created templates or designs, it does not have options to change the design.

## Preview

![agency](https://user-images.githubusercontent.com/114579121/193446865-ef500949-f3f9-4374-9c27-32d2fb7d43f5.gif)

Demo: https://thenocoder.github.io/ncSimpleHtmlEditor/demo/grayscale/

## Basic Usage

Download your template from here https://startbootstrap.com/theme/agency or any other from here: https://github.com/StartBootstrap

Add this code at the end of index.html, immediately before /body:

```javascript
<div id="ncsedt-implement">
    <link href="https://cdn.statically.io/gh/thenocoder/ncSimpleHtmlEditor/master/ncsimplehtmleditor.css" rel="stylesheet" />
    <script src="https://cdn.statically.io/gh/thenocoder/ncSimpleHtmlEditor/master/ncsimplehtmleditor.js"></script>
    <script>
        window.addEventListener('DOMContentLoaded', function () {
            if (!("ncSHEditor" in window)) {
                ncSHEditor = new ncSimpleHtmlEditor();
                ncSHEditor.start();
            }
        });
    </script>
</div>
```

When you finish editing your template click on save, you get an index.html file that you must replace with the one you downloaded with the template.

And that's it!

## Advanced Usage

Go: https://github.com/TheNocoder/ncSimpleHtmlEditor

## Copyright and License

MIT license
