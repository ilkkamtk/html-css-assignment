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
* Web page(s) don't need to be responsive.

### How to submit:
In Oma, provide a `clickable` link to the folder where your assignment is. Also provide a `clickable` link to the html document where you have the screenshots and the css example of your font. See the [video](https://www.youtube.com/watch?v=u7mjd5Vi6lk&list=PLKenVLUxjmH-y89AiiI2xcXDy5QG83D4K&index=6) for details. Example submission:

[Site](https://users.metropolia.fi/~username/foldername)

[Screenshots](https://users.metropolia.fi/~username/foldername/screenshots.html)

### Evaluation
On submission, you will automatically receive grade 5. If some aspects of the assignment are missing or inadequate, grade will be deducted as follows:
* Your version does not resemble the provided layout, or CSS is missing -1 to -3
* Navigation does not work -3
* Images are not found -3
* Contrast check is not passed -2
   * UPDATE 28.10.2024: https://color.a11y.com/Contrast/ is no longer available. Use https://wave.webaim.org/ instead. [Example screenshot here](wave.png).
* Validation is not passed -3
   * No errors
   * Warnings, like no heading in `<article>` or `<section>` etc. are allowed
* Lighthouse check score is less than 90 -1, less than 70 -2
  * some versions of Chrome show the score with 5/5 or 4/4 in that case -1 from each missing point. E.g. 3/4 = -1. However, max deduction is -2
  * Update 25.3.2024: If you use `<iframe>` to add Google map, Lighthouse will deduct points. That will not affect evaluation. you should however conisder just using an image of the map. 
* Default font (Times New Roman) -2
* Missing padding (text too close to edges or other elements) -2

**Note! Test your assignment on a different computer to make sure all files are loaded!** 

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
