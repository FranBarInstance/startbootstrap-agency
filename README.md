# [Editor for template content](https://github.com/FranBarInstance/simple-html-editor)

Allows you to edit the content of previously created templates or designs, it does not have options to change the design.

## Preview

[![screencast](https://user-images.githubusercontent.com/114579121/193446865-ef500949-f3f9-4374-9c27-32d2fb7d43f5.gif)](https://franbarinstance.github.io/simple-landing-editor/landing/)

## Demo

[https://franbarinstance.github.io/simple-html-editor/demo/agency/](https://franbarinstance.github.io/simple-html-editor/demo/agency/)

[https://franbarinstance.github.io/simple-landing-editor/landing/](https://franbarinstance.github.io/simple-landing-editor/landing/)

## Basic Usage

Download your template from here https://startbootstrap.com/theme/agency or any other from here: https://github.com/StartBootstrap

Add this code at the end of index.html, immediately before /body:

```html
<!-- ncsedt-implement:before -->
<div id="ncsedt-implement">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/FranBarInstance/simple-html-editor@1.0.1/simplehtmleditor.min.css">
    <script src="https://cdn.jsdelivr.net/gh/FranBarInstance/simple-html-editor@1.0.1/simplehtmleditor.min.js"></script>
    <script>
        window.addEventListener('DOMContentLoaded', function () {
            var editor = new ncSimpleHtmlEditor();
            editor.start();
        });
    </script>
</div>
<!-- ncsedt-implement:end -->
```

When you finish editing your template click on save, you get an index.html file that you must replace with the one you downloaded with the template.

And that's it!

## Advanced Usage

Go: [https://github.com/FranBarInstance/simple-html-editor](https://github.com/FranBarInstance/simple-html-editor)

## Copyright and License

MIT license
