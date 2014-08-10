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
