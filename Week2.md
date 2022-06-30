# HTML

Key themes: syntax compatible with html 4 and xhtml1.
Separates conformance requirements for user agents and authors.
HTML5 includes APIS in creating webapps. Video, audio, docs.

Use style sheets do display pages in differnet brows or mobile.
APIs for enhaced UX.
Inproved page load times.
Search Index indexing.

Structural elements: section, article header, footer, etc-
Canvas, audio video (embedded content)
Input elements: attributes: tel, email, etc.

Web storage. Web workers.

## HTML Scripting

Every HTML and XML documents is represented by a Document Object.

DOM properties:
Head, title, images, lastModified, Scripts.

Scripting: more interactive user exp.
not to lrely on it.

iframe mashups.

## HTML5 Browser support

Not all browsers fully support all HTML5 and CSS3.

Chrome support most features. caniuse.com

```HTML
<input type = "date">
```

You can use JS to check HTML5 supported by a browser:

```javascript
document.createElement() //To dinamically create the elelemt
//Check for elements in <script html>
var datePicker = document.createElement("input");
var formelement = document.getElementById("Thisform");
```

Not all browser supports HTML5 and CSS3. Caniuse.com

## CSS

Android, iOS and tables suppports HTML5.
No flash in iOS.

No requirement to download potentially insecure precompiled binary files.

CSS: layered cascade style sheet. Cascasing applies a uniform look through each page of website.

Separate de data from design.

External documents (style sheets)

### Fluid or fixed layout

Fluid: elements expand or contract based on the browser.
Fixed: specify the height and width of elements.
