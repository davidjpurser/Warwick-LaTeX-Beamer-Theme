This is an *unofficial* LaTeX Beamer theme modelled roughly after the website of the University of Warwick.

It is heavily extended from [a theme by Patrick Totzke][from]

See `example-pres.pdf` for a demo.

To use it place the `logo-with-descriptor.pdf` and `.sty` and the files where latex can find them and include
`\usetheme{Warwick}` in your preamble.


It has several options, e.g.

`\usetheme[style=blue,external]{Warwick}`

* `externalfront` shows 'The University of Warwick' below 'Warwick' only on the title page.
* `external` shows 'The University of Warwick' below 'Warwick' on every page. (`externalfront` is subsumed under this option).
* `style` is one of `aubergine,blue,ruby,orange,gold`. Default is blue.
* `nowarwickmain` turns off the Warwick logo on normal slides. stays only on the front

If you don't want to brand as Warwick, but just use the colours and `\warwicklogo`:
* `supresswarwick` turns off the Warwick logo in the right corner everywhere (subsumes `nowarwickmain`. Further `externalfront`,`external` are irrelevant under this option.)

The command `\warwicklogo{#1}` provides the Warwick logo of size `#1` (with The University of Warwick) in the colour of the theme. Useful for the front page. (If updating, previous versions did not have the size parameter)

[from]: https://github.com/pazz/beamerthemeWarwick
