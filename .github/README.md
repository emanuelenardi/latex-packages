

# LaTeX



This repository contains the libraries that I use on daily basis to typesetting my TeX based documents.

## Utilizzo

Clone questa repository nella tua cartella locale `texmf`, poi esegui il comando `texhash` sul terminale.
<!-- Clone this repo in your local `texmf` folder , then run `texhash` command on a terminal. -->

Se sei su Windows, esegui il seguente comando:
<!-- If you are on a Windows system run the following: -->
```bash
git clone https://github.com/emanuelenardi/latex C:\texlive\texmf-local\tex && texhash
```

Mentre se sei su un sistema basato su UNIX (come linux o mac), esegui il seguente comando:
<!-- While if you're on UNIX based system (like linux or mac) run the following: -->
```bash
git clone https://github.com/emanuelenardi/latex ~/usr/local/share/texmf/tex && texhash
```

## Descrizione dei pacchetti
<!-- ## Description of the packages -->

Le dipendenze dei pacchetti sono listate come sottopunti nella lista puntata sotto.
<!-- Package dependencies are listes are subitems in the bullet list below. -->

<!-- - [`coffee4` — it adds a coffee stain to your documents ([reference site][1]); -->

<!-- - [`exam` — A template for typesetting exams; -->

<!-- - [`introduction` — This is the standard introduction that I use for my lecture notes; -->




* `tikz-er2` — it permits to draw ER diagrams with `tikz`
* `tikz-uml` — it permits to draw UML diagrams with `tikz`.

* `ams-all` —
* `debug` —
* `front-page` — A template for the initial page of my lectures notes
* `local` — A folder already present on the file system ( _don't_ delete it )
* `my-macros` —
- [`my-preamble` — The preamble in which I've listed all the libraries I ordinarily use in my doc
* `pgf-umlsd` —
* `set-algorithm2e` —
* `set-automata` —
* `set-background` —
* `set-caption` —
* `set-citations` —
* `set-color` —
* `set-date` —
* `set-external-files` —
* `set_forest` — settings for the `forest` package
	<!-- * `set-forest-android` — -->
* `set-geometry` —
* `set-graphics` —
* `set-highlights` —
* `set-license` —
* `set-links` —
* `set-listing` — settings for the `lstlisting` package
	* `set-listing-languages` — it defines the programming languages that I normally use
	- [`set-listing-styles` — it defines the styles in which I want the programming languages to be displayed with
* `set-lists` — liste puntate
* `set-math` — pacchetti matematici
* `set-microtype` — migliora la resa del testo
* `set-minted` — per importare listati
* `set-notes` — note a margine
* `set-pages` — pagine bianche e contatori
* `set-paragraph` — indentazione dei paragrafi
* `set-pdf-props` —
* `set-quote` —
* `set-rotating` —
* `set-tables` —
* `set-tikz` — impostazioni del pacchetto `tikz`
	* `set-tikz-externalization` —
	* `set-tikz-graphs` —
	* `set-tikz-macros` —
* `set-toc` —
* `set-uml` — impostazioni per il pacchetto `tikz-uml`
* `set-utilities` —

* `tikz-er2` — permette di disegnare diagrammi ER con `tikz`
* `tikz-uml` — permette di disegnare diagrammi UML con `tikz`
<!-- * `tikz-uml-set` — -->

<!-- ## Code formatting

Code formatting in my latex documents follow a strict legend that is listed below.

| Colore | Simbolo | Codice |
| --- | --- | --- |
| SkyBlue | `•...•` | `alt + 149` |
| celeste | `Ž...Ž` | `alt + 0142` |
| ForestGreen | `†...†` | `alt + 0134` |
| green | `+++...+++` | `+` |
| yellow | `‡...‡` | `alt + 0135` |
| orange | `Š...Š` | `alt + 0138` |
| red | `---...---` | `-` | -->

<!-- ## Contribute

Fork this repository, make your changes and then issue a pull request.
If you find bugs or have new ideas that you do not want to implement yourself, file a bug report. -->

## Copyright

Copyright (c) 2017 — 2019 Emanuele Nardi.

<!-- TODO -->
Licenza: [MIT]()

<!-- [1]: http://hanno-rein.de/archives/349 -->
