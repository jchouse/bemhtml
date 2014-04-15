# bemhtml language support in Atom

Adds syntax highlighting and snippets to bemhtml file in Atom.

Originally (https://github.com/atom/language-javascript).

Based (https://github.com/feugenix/BEMHTMLSublime).

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

## Upgrade

To upgrade pkg, reinstall with shell command 'rm -rf bemhtml && apm instal bemhtml' in /Users/username/.atom/packages

## Snippets
**don't be afraid to press ⇥**

block
    `b` -> `block blockName,`

elem
    `e` -> `elem elemName,`

block + elem
    `be` -> `block blockName, elem elemName,`

mod
    `m` -> `mod modName modValue,`

elemMod:
    `em` -> `elemMod modName modValue,`
