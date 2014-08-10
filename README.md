Aptitude
========

Aptitude is a super-simple theme for one-page articles and projects.

![Screenshot](https://cloud.githubusercontent.com/assets/2841780/3857456/7b836d9a-1f03-11e4-8578-e16a7d263a9d.jpg "Screenshot")

Usage
=====

Add these three CSS files to your head:

`//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css`
`//cdn.rawgit.com/AnandChowdhary/normalize.css/master/normalize.min.css`
`//cdn.rawgit.com/AnandChowdhary/aptitude/master/aptitude.min.css`

Then, follow the structure in the demo.html file and create your page.

Finally, make a Typekit kit with *Adobe Garamond Pro* and *Calluna Sans* and add its code before your body ends.

Alternatively, download demo.html and go crazy.

Tips
====

For a custom accent color, replace "#e44249" in aptitude.css, or, if you're using the CDN, replace X with your accent color and add the following to your head:

```
<style type="text/css">
  a:hover, h1.title {
    color: X
  }
  a:focus {
    background: X
  }
  blockquote {
    border-color: X
  }
</style>
```

Too add more websites to "Share" links, add a new link with a Font Awesome icon of that website, like `<a target="_blank" href="//facebook.com/anand.chowdhary"><i class="fa fa-facebook-square"></i></a>` in `.half` in the footer.

Credits
=======

- [Font Awesome](http://fontawesome.io) by Dave Gandy
- [Normalize.css](http://necolas.github.io/normalize.css/) by Nicolas Gallagher and Jonathan Neal
- [Adobe Garamond Pro](http://store1.adobe.com/cfusion/store/html/index.cfm?event=displayFontPackage&code=1703) and [Calluna Sans](https://typekit.com/fonts/calluna-sans) are delivered by Typekit
- Developed and maintained by [Anand Chowdhary](http://anandchowdhary.com)

License
=======

Copyright (c) 2014 Anand Chowdhary (anandchowdhary@gmail.com).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
