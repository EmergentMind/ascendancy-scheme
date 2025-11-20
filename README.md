<div align="center">
<h1> Ascendancy Colour Scheme</h1>
<img src="tinted-theming-schemes-gallery.png" />
</div>


> The Ascendancy colour scheme aims to provide a comforting spectrum of background and foreground shades, complimented by soft but regal colours.
> 
> The palette has a small bias towards golden colours without creating a sense of washed out overexposure.

## Palette
| colour                                                | base0X | hex       | terminal equivalent | base 16 styling guidelines |
| --------------------------------------------------   | ------ | -------   | -------------       | ---------------                                                                           |
| ![#](https://placehold.co/25/282828/000000?text=%2B) | base00 | `#282828` | ----                | Default Background                                                                        |
| ![#](https://placehold.co/25/212f3d/000000?text=%2B) | base01 | `#212f3d` | ---                 | Lighter Background (Used for status bars, line number and folding marks)                  |
| ![#](https://placehold.co/25/504945/000000?text=%2B) | base02 | `#504945` | --                  | Selection Background                                                                      |
| ![#](https://placehold.co/25/928374/000000?text=%2B) | base03 | `#928374` | -                   | Comments, Invisibles, Line Highlighting                                                   |
| ![#](https://placehold.co/25/bdae93/000000?text=%2B) | base04 | `#bdae93` | +                   | Dark Foreground (Used for status bars)                                                    |
| ![#](https://placehold.co/25/d5c7a1/000000?text=%2B) | base05 | `#d5c7a1` | ++                  | Foreground, Caret, Delimiters, Operators                                                  |
| ![#](https://placehold.co/25/ebdbb2/000000?text=%2B) | base06 | `#ebdbb2` | +++                 | Light Foreground (Not often used)                                                         |
| ![#](https://placehold.co/25/fbf1c7/000000?text=%2B) | base07 | `#fbf1c7` | ++++                | Lightest Foreground (Not often used)                                                      |
| ![#](https://placehold.co/25/c03900/000000?text=%2B) | base08 | `#c03900` | red                 | Vars, XML Tags, Markup Link Text, Markup Lists, Diff Deleted                              |
| ![#](https://placehold.co/25/fe8019/000000?text=%2B) | base09 | `#fe8019` | orange              | Integers, Boolean, Constants, XML Attributes, Markup Link Url                             |
| ![#](https://placehold.co/25/ffcc1b/000000?text=%2B) | base0A | `#ffcc1b` | yellow              | Classes, Markup Bold, Search Text Background                                              |
| ![#](https://placehold.co/25/b8bb26/000000?text=%2B) | base0B | `#b8bb26` | green               | Strings, Inherited Class, Markup Code, Diff Inserted                                      |
| ![#](https://placehold.co/25/8f3f71/000000?text=%2B) | base0C | `#8f3f71` | cyan                | Support, Regular Expressions, Escape Characters, Markup Quotes                            |
| ![#](https://placehold.co/25/458588/000000?text=%2B) | base0D | `#458588` | blue                | Functions, Methods, Attribute IDs, Headings                                               |
| ![#](https://placehold.co/25/fabd2f/000000?text=%2B) | base0E | `#fabd2f` | magenta             | Keywords, Storage, Selector, Markup Italic, Diff Changed                                  |
| ![#](https://placehold.co/25/b59b4d/000000?text=%2B) | base0F | `#b59b4d` | darkred             | Deprecated, Opening/Closing Embedded Language Tags, e.g. `<?php ?>`                       |


This scheme is also hosted on the [tinted-theming/schemes](github.com/tinted-theming/schemes) repository; it can easily be applied to your environment by using any utility that references `tinted-theming` for colour schemes.

For example, on NixOS, the scheme can be conveniently applied to your environment using utilities such as [stylix](https://github.com/nix-community/stylix) or [base16.nix](https://github.com/SenchoPens/base16.nix).

## Acknowledgements

Inspired by the [Gruvbox](https://github.com/morhetz/gruvbox) Dark, Medium scheme as a starting point.
