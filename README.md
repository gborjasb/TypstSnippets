# Typst Snippets

This extension includes a variety of snippets for **Typst**.

## Usage
1. Open a file with the `.typst` extension.
2. Type a snippet shortcut and press `Tab` to expand it.

## Features

Snippets start with `@` or with the initials of the commands

### Greek Letters

| Trigger | Snippet | Character |
| ------- | ------- | --------- |
| `@a` | `alpha` | $\alpha$ |
| `@b` | `beta` | $\beta$ |
| `@c` | `chi` | $\chi$ |
| `@d` | `delta` | $\delta$ |
| `@e` | `epsilon` | $\epsilon$ |
| `@f` | `phi` | $\phi$ |
| `@g` | `gamma` | $\gamma$ |
| `@h` | `eta` | $\eta$ |
| `@i` | `iota` | $\iota$ |
| `@k` | `kappa` | $\kappa$ |
| `@l` | `lambda` | $\lambda$ |
| `@m` | `mu` | $\mu$ |
| `@n` | `nu` | $\nu$ |
| `@p` | `pi` | $\pi$ |
| `@q` | `theta` | $\theta$ |
| `@r` | `rho` | $\rho$ |
| `@s` | `sigma` | $\sigma$ |
| `@t` | `tau` | $\tau$ |
| `@u` | `upsilon` | $\upsilon$ |
| `@o` | `omega` | $\omega$ |
| `@x` | `xi` | $\xi$ |
| `@y` | `psi` | $\psi$ |
| `@z` | `zeta` | $\zeta$ |
| `@D` | `Delta` | $\Delta$ |
| `@F` | `Phi` | $\Phi$ |
| `@G` | `Gamma` | $\Gamma$ |
| `@Q` | `Theta` | $\Theta$ |
| `@L` | `Lambda` | $\Lambda$ |
| `@X` | `Xi` | $\Xi$ |
| `@Y` | `Psi` | $\Psi$ |
| `@S` | `Sigma` | $\Sigma$ |
| `@U` | `Upsilon` | $\Upsilon$ |
| `@W` | `Omega` | $\Omega$ |
| `@ve` | `varepsilon` | $\varepsilon$ |
| `@vf` | `varphi` | $\varphi$ |
| `@vs` | `varsigma` | $\varsigma$ |
| `@vq` | `vartheta` | $\vartheta$ |

### Operators

| Trigger | Snippet | Character |
| ------- | ------- | --------- |
| `@8` | `infinity` | $\infty$ |
| `EE` | `exists` | $\exists$ |
| `FF` | `forall` | $\forall$ |
| `@*` | `times` | $\times$ |
| `@6` | `partial` | $\partial$ |
| `@=` | `equiv` | $\equiv$ |

### Math Functions

| Trigger | Snippet | Description |
| ------- | ------- | ----------- |
| `FRAC` | `frac($1, $2)` | Fraction |
| `@sq` | `sqrt($1)` | Square root |
| `@root` | `root($2, $1)` | Root |

### Text Fonts

| Trigger | Snippet | Description |
| ------- | ------- | ----------- |
| `TBF` | `*$1*` | Bold text |
| `TIT` | `_$1_` | Italic text (used for emphasis) |
| `TSC` | `#smallcaps[$1]` | Smallcaped text |
| `TUL` | `#underline[$1]` | Underlined text |
| `TOL` | `#overline[$1]` | Overlined text |
| `TUC` | `#upper[$1]` | Text in uppercase letters |
| `TLC` | `#lower[$1]` | Text in lowercase letters |
| `TSP` | `#super[$1]` | Superscript text |
| `TSB` | `#sub[$1]` | Subscript text |
| `TST` | `#strike[$1]` | Striked text |
| `TCODE` | ` ``${1:language} \n\n`` ` | Code text |

### Math Fonts

| Trigger | Snippet | Description |
| ------- | ------- | ----------- |
| `MBF` | `bold($1)` | Bold math text |
| `MSR` | `serif($1)` | Default roman math font |
| `MSS` | `sans($1)` | Sans-serif math font |
| `MFR` | `frak($1)` | Fraktur (Gothic) math font |
| `MTT` | `mono($1)` | Monospaced math font |
| `MBB` | `bb($1)` | Blackboard bold math font |
| `MCA` | `cal($1)` | Calligraphic math font |

### Figures

| Trigger | Snippet | Description |
| ------- | ------- | ----------- |
| `FIG` | `#figure(\n ${1:content} ,\ncaption : [${2:caption}]\n)<${3:reference}>` | Figure |

### Tables

| Trigger | Snippet | Description |
| ------- | ------- | ----------- |
| `TABLE` | `#table(\n columns: ${1:columns},\n //// align: ,\n table.header[${2:header}],\n [${3:data}]\n)` | Table |

More support for mathematics such as Analysis, Measure Theory, Algebra, etc., will be added.

## Inspiration

This project was inspired by the [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) extension developed by James Yu. We appreciate his contribution to the LaTeX community.

## Suggestions

Please let us know what other snippets you would like to see.