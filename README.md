LaTeX Package for Papers at IPZ
===============================


TODO Kurzbeschrieb


Usage
-----

Zur Verwendung das Paket erstmal mit  `\usepackage{IPZstyle}` laden.
Beim Laden können Paketoptionen (s.u.) angegeben werden. 


### Paketoptionen

* Kodierung der .tex-Datei: os = [win (default) | mac | unicode]
* Sprache: lang = [de (default) | en]

### Titelseite

Das Paket definiert den `\maketitle` Befehl um, so dass die Titelseite
den Standardanforderungen des IPZ genügt. Folgende Elemente können (in 
der Präambel) angegeben werden:

* `\title{Arbeit}`
* `\subtitle{Untertitel}`
* `\course{Kursbeschrieb}`
* `\date{Abgabedatum}`
* `\lecturer{Dozent}`
* `\term{Semester}`
* `\type{Typ der Arbeit}`
* `\author{Autor}`
* `\authorinfo{Adresse\\
  Matrikelnummer\\
  weitere Infos}`

Author
------
* Christian Mueller

