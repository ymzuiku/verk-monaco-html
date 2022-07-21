# use verk render monaco

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Verk</title>
    <link
      rel="icon"
      href="https://unpkg.com/verk-monaco-html@0.0.2/favicon.ico"
    />
  </head>
  <script src="https://unpkg.com/verk-monaco-html@0.0.2/js/verk.min.js"></script>
  <body>
    <div>
      <v-new src="./monaco/monaco_verk_editor.html" />
    </div>
  </body>

  <script>
    window.customCode = `console.log("hello monaco")`;
    window.customLanguage = "typescript";
  </script>
</html>
```
