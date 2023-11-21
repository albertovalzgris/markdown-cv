# markdown-cv

A curriculum vitae maintained in plain text and rendered to HTML and PDF using CSS.

Forked from [Eliseo Papa's original](http://elipapa.github.io/markdown-cv).

## Updating & exporting

1. `cd` into repository
1. Switch to `gh-pages` branch
1. Edit `index.md` in local editor
1. `git add .`
1. `git cm -m "message"`
1. Push to branch `gh-pages` typing `git push origin gh-pages`
1. See output on [github](https://albertovalzgris.github.io/markdown-cv/)
1. Print pdf by typing `wkhtmltopdf -g https://albertovalzgris.github.io/markdown-cv/ output/avg-cv-eng.pdf`
1. Merge `gh-pages` into `master`?
1. Done!

## Author

Eliseo Papa ([Twitter](http://twitter.com/elipapa)/[Github](http://github.com/elipapa)/[Website](https://elipapa.github.io)).

## License

[MIT License](https://github.com/elipapa/markdown-cv/blob/master/LICENSE)
