# asciidoctor-mlpushmenu-template
A custom haml template for Asciidoctor with a [multi-level push menu](http://tympanus.net/codrops/2013/08/13/multi-level-push-menu)

Run `asciidoctor -T custom-html5 index.adoc` will convert your index.adoc into index.html with the template layout.

`css` `fonts` and `js` folder should be at the same level in the directory as the html file, i.e. the directory should look like this:

- index.html
- css/
- fonts/
- js/
- ...

A sample from Taiga documentation is added for preview (taiga-sample.adoc and taiga-sample.html). Another set of sample is from [asciidoctor-backends](https://github.com/asciidoctor/asciidoctor-backends) README.adoc in which I added a line `:toclevels: 3` so that it demonstrates 3-levels push menu (asciidoctor-backends-readme.adoc and asciidoctor-backends-readme.html).

The template is currently under testing and development.
