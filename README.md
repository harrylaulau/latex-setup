# How to setup local latex in vscode

## Initial setup

1. Install LaTex Workshop, LaTeX Utilities in vscode extensions
2. Install BasicTex cask, perl, latexindent, ghostscript from brew
3. Follow instruction to setup perl. See `brew info perl`
4. Update tlmgr by `tlmgr update --self`
5. Install latexmk, chktex, texcount with tlmgr `sudo tlmgr install latexmk`
6. Install biber, biblatex with tlmgr, note that biblatex is not compatible with natbib
7. Install emptypage, subfigure, adjustbox, wrapfig, capt-of, multirow, acronym, suffix, bigfoot, xstring, glossaries, sectsty, csquotes, biber with tlmgr
8. Config Latex Workshop recipe to use biber
9. Set latexindent path in settings of LaTex Workshop extension
10. Install Zotero
11. Install Code Spell Checker in vscode extensions
12. Write latex!

