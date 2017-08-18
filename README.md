# bemhtml language support in Atom

Adds syntax highlighting and snippets to bemhtml file in Atom.

Originally (https://github.com/atom/language-javascript).

Based (https://github.com/feugenix/BEMHTMLSublime).

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

## Snippets
**don't be afraid to press ⇥**

block `b` -> `block blockName,`

block `b:` -> `block: 'blockName',`

elem `e` -> `elem elemName,`

elem `e:` -> `elem: 'elemName',`

block + elem `be` -> `block blockName, elem elemName,`

mod `m` -> `mod modName modValue,`

mods `m:` -> `mods: { modName: 'modValue' },`

elemMod `em` -> `elemMod modName modValue,`

elemMods `em:` -> `elemMods: { modName: 'modValue' },`

mix `mi:` -> `mix: [ { block: blockName } ]`

content `c:` -> `content: [ { ... } ]`

js `js:` -> `js: { ... }`

tag `t:` -> `tag: 'tagName',`

attrs `a:` -> `attrs: { ... }`

cls `cl:` -> `cls: 'className',`

bem: false `bf:` -> `bem: false`
