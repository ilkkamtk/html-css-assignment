# HTML + CSS Assignment
### Make your version of [the provided layout](assingment-layout.pdf).
* In the provided layout you'll find the plans for three pages: Home, Products and Contact.
* Your task is to make a simple website using the provided layout.
* The result does not have to be pixel-perfect. It's enough that the visual structure is close to the provided layout.
* You can have the three pages in one document, or you can put each page into its own document.
* You should make up your own color palette and choose a font (or fonts) for your version.
* Also add your own images to the page(s).
* You can use lorem ipsum as text content. Any text will do.
* You don't have to consider copyrights, since this is an educational assignment.
* More detailed description in the video provided in Oma.

### How to submit:
In Oma, provide a `clickable` link to the folder where your assignment is. Also provide a `clickable` link to the html document where you have the screenshots and the css example of your font. See the video for details. Example submission:

[Site](https://users.metropolia.fi/~username/foldername)

[Screenshots](https://users.metropolia.fi/~username/foldername/screenshots.html)

### Evaluation
On submission, you will automatically receive grade 5. If some aspects of the assignment are missing or inadequate, grade will be deducted as follows:
* Your version does not resemble the provided layout, or CSS is missing -1 to -3
* Navigation does not work -3
* Images are not found -3
* Contrast check is not passed -2
* Validation is not passed -3
* Lighthouse check is incomplete -1/audit
* Default font (Times New Roman) -2
* Missing padding (text too close to edges or other elements) -2
* Did not follow submission instructions -5

Screenshot page example html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Results</title>
</head>
<body>
<h2>Font</h2>
<p>Font is from <a href="https://fonts.google.com/specimen/Whatever">Google Fonts. Name: Whatever</a></p>
<pre>
    @font-face {
      font-family: whatEver;
      src: url(sansation_light.woff) format(woff);
    }

    body {
       font-family: whatEver;
    }
</pre>
<h2>Validation</h2>
<p>
    <img src="img/validator.png" alt="valid">
</p>
<h2>Lighthouse</h2>
<p>
    <img src="img/lighthouse.png" alt="lighthouse">
</p>
<h2>Contrast</h2>
<p>
    <img src="img/contrast.png" alt="contrast">
</p>

</body>
</html>
```
