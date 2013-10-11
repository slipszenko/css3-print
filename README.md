css3-print
==========

A template for my CSS3 printing stylesheet. Will be used a submodule in all papers I have to write.

Unfortunately
```css
@page { @bottom-right { /* content such as page numbers */ } }
```
doesn't seem to work yet in any major browser, somewhat limiting the usefulness of this until that changes.


To use, just include the file into your page with the media set to print:
```html
<link rel="stylesheet" href="/lib/css3-print/print.css" media="print" />
```

Resources used:
* http://dev.w3.org/csswg/css-gcpm/
* http://www.w3.org/TR/css3-page/