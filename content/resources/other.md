---
title: Other resources
linktitle: Other resources
toc: true
type: docs
draft: false
date: 2020-05-01T12:00:00Z
menu:
  resources:
    name: Other resources
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

**Useful links:**

*   [**SciFinder**](https://scifinder.cas.org/) - essential literature searching
*   [**Reaxys**](https://www.reaxys.com/) - essential literature searching
*   [**Web of Science**](http://login.webofknowledge.com/error/Error?Error=IPError&PathInfo=%2F&RouterURL=http%3A%2F%2Fwww.webofknowledge.com%2F&Domain=.webofknowledge.com&Src=IP&Alias=WOK5) - essential literature searching
*   [**CCDC search**](https://www.ccdc.cam.ac.uk/structures/?) - crystal structure search
*   [**Aldrich substructure search**](https://www.sigmaaldrich.com/catalog/search/substructure/SubstructureSearchPage)
*   [**CAS List of Journal Abbreviations**](https://www.cas.org/support/documentation/references/corejournals) - useful list of journal abbreviations in case you ever wish to check
*   [**Chemistry Reference Resolver**](http://chemsearch.kovsky.net/) - saves huges amounts of time by resolving chemistry references (of the form JACS 2011 11211) into URLs for you. No more need to navigate journal web-pages. From my testing: ACS and RSC journals don't need volume numbers. For Tetrahedron and Tet. Lett.: skip the year, and give a volume number instead.
*   [**Feedspot**](https://www.feedspot.com/) - replacement for Google Reader (for those who remember it), or for others: a good way to keep up to date with journal articles.

**Useful Chrome Extensions:**

*   [**Chemistry Reference Resolver**](http://chemsearch.kovsky.net/extensions.php)
    *   Gives you a button in which you can type chemistry references (e.g. "jacs 2011 11211") to resolve them to article pages. Also adds a search engine to Chrome: you can type "ref" <TAB> "jacs 2011 11211" <ENTER> to search directly from the Omnibar.
*   [**Google Scholar**](https://chrome.google.com/webstore/detail/google-scholar-button/ldipcbpaocekfooobnbcddclnhejkcpn?hl=en)
    *   Paste a reference title, and it can probably resolve it to a PDF for you.
*   [**POPF!**](https://chrome.google.com/webstore/detail/piss-off-publisher-frames/ffmffcaeblfpligkklopofadiemkelld?hl=en)
    *   Takes you to an actual PDF of an article, not a ReadCube file or something full of frames.

**Setting up the Chemistry Reference Resolver as a search engine in Chrome**\[UPDATE: the current version of the Chemistry Reference Resolver Extension does all of this for you, but with the "ref" keyword\]:

1.  Go to [**chrome://settings/searchEngines**](chrome://settings/searchEngines)
2.  Click "ADD" to the right of "Other search engines"
3.  Fill in the fields as follows
    1.  **Search engine**: RefResolver (or whatever you like)
    2.  **Keyword**: cs
    3.  **URL**: **http://chemsearch.kovsky.net/?q=%s**
4.  Press SAVE
5.  Type "cs" <TAB> "JACS 2011 11211" <ENTER>
6.  The reference will be resolved, like magic

You can do the same for other sites. For example, I have the keyword "sa" set up for Aldrich, with the following search URL: "**http://www.sigmaaldrich.com/catalog/search?interface=All&term=%s"**

**LaTeX:**

I wrote my chemistry DPhil thesis in LaTeX, which carried with it a learning curve. Here are links to some useful packages, and a script or two of my own.

*   [**TeX stackexchange**](https://tex.stackexchange.com/): not a package, but an infinite source of wisdom
*   [**chemnum**](https://www.ctan.org/pkg/chemnum?lang=en): numbers chemistry compounds by editing EPS files written by ChemDraw. Read the manual - it's a bit fiddly, but worth it.
*   [**siunitx**](https://www.ctan.org/pkg/siunitx?lang=en): handles SI units elegantly
*   [**nomencl**](https://www.ctan.org/pkg/nomencl?lang=en): will generate your list of abbreviations for you
*   [**Detexify**](http://detexify.kirelabs.org/classify.html): converts handwritten symbol into LaTeX command
*   [**The Oxford Thesis Class**](https://www.oxfordechoes.com/oxford-thesis-template/) which I started from. My changes (in the form of my thesis.tex and revised class file) are on Github [**here**](https://github.com/martinp23/thesis-public). The Github repository includes the first two chapters of my thesis.

**Alt-Codes**

You need a keyboard with a separate number pad to use these Alt-codes. To type these symbols, hold down Alt and type the three- or four-character code on the number pad. On Windows, to find more Alt codes use the Character Map program. Browse through it to find the symbol you want, and the Alt code appears in the bottom right.

||||||
|--- |--- |--- |--- |--- |
|Symbol|Alt Code||Symbol|Alt Code|
|en-dash –|0150||times ×|0215|
|em-dash —|0151||divide ÷|0247|
|minus −|8722||\pm ±|0177|
|bullet •|0149||Mu µ|0181|
|cdot ·|0183||Angstrom Å|0197|
|degree °|0176||\"a ä|0228|
|GBP £|156||\"o ö|0246|
|Euro €|0128||nbsp|0160|
