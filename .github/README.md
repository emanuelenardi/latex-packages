# LaTeX

Questa repository contiene i frammenti di codice che uso su base giornaliera per impaginare i miei documenti LaTeX.
<!-- This repository contains the libraries that I use on daily basis to typesetting my TeX based documents. -->

## Utilizzo

Effettua una copia di questa repository nella tua cartella locale `texmf`, poi esegui il comando `texhash` sul terminale.
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

<!-- - [`exam` — A template for typesetting exams -->

<!-- - [`introduction` — This is the standard introduction that I use for my lecture notes -->

### Pacchetti esterni

- `tikz-er2` — it permits to draw ER diagrams with `tikz`
- `tikz-uml` — it permits to draw UML diagrams with `tikz`.
- `pgf-umlsd` — it permits to draw UML di­a­grams us­ing pgf

### I miei frammenti di codice

- `ams-all` — un semplice pacchetto che carica i pacchetti matematici nel giusto ordine
- `debug` — carica i pacchetti `showframe` e `showlabel` per avere una chiara idea di margini ed etichette presenti nel documento
- `front-page` — A template for the initial page of my lectures notes
- `local` — A folder already present on the file system ( _don't_ delete it )
- `my-macros` — comandi personali
- `my-preamble` — The preamble in which I've listed all the libraries I ordinarily use in my doc
- `set-algorithm2e` — personalizzazione del pacchetto `algorithm2e`
- `set-automata` — personalizzazione del pacchetto `automata`, presto diventerà un pacchetto a sé stante
- `set-background` — personalizzazione del pacchetto `algorithm2e`
- `set-citations` — pacchetto estratto da [questa risposta](tex.stackexchange.com/questions/53377/)
- `set-color` — personalizzazione del pacchetto `xcolor`
- `set-date` — personalizzazione del pacchetto `datetime2`
- `set-external-files` —
- `set-forest` — settings for the `forest` package
	- `set-forest-android` — Un pacchetto _soon to be removed_ di un vecchio documento
- `set-geometry` — personalizzazione del pacchetto `geometry`
- `set-graphics` — personalizzazione del pacchetto `graphicx`
- `set-highlights` — personalizzazione del pacchetto `ulem`
- `set-license` — personalizzazione del pacchetto `doclicense`, utilizzato spesso in combinazione con `background`.
- `set-links` — personalizzazione del pacchetto `hyperref`
- `set-listing` — settings for the `lstlisting` package
	- `set-listing-languages` — it defines the programming languages that I normally use
	- `set-listing-styles` — it defines the styles in which I want the programming languages to be displayed with
- `set-lists` — personalizzazione del pacchetto `enumitem`
- `set-math` — personalizzazione del pacchetto `doclicense`
- `set-microtype` — migliora la resa del testo
- `set-minted` — per importare listati con il
- `set-notes` — note a margine
- `set-pages` — pagine bianche e contatori
- `set-paragraph` — indentazione dei paragrafi
- `set-pdf-props` — personalizzazione del pacchetto `hyperref`
- `set-quote` — personalizzazione del pacchetto `csquotes`
- `set-rotating` — funzionalità di rotazione della pagina/tabelle
- `set-tables` — funzionalità per tabelle
- `set-tikz` — impostazioni del pacchetto `tikz`
	- `set-tikz-externalization` — funzionalità di caching per grafici
	- `set-tikz-graphs` — caricamento dei pacchetti per il disegno di grafici ER/UML
	- `set-tikz-macros` — semplici commandi
- `set-toc` — ridefinizione della "table of contents"
- `set-uml` — impostazioni per il pacchetto `tikz-uml`
- `set-utilities` — pacchetti che carico quasi sempre nei miei documenti
