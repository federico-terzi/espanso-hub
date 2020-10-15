---
package_name: "french-accents"
package_title: "French Accents"
package_desc: "A package to type French with a non-French keyboard layout. It works by replacing keywords like e' with é."
package_version: "0.1.0"
package_author: "Otto Piramuthu"
package_original_repo: "https://github.com/ottopiramuthu/espanso-package-example"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}
 
A simple package to conveniently type French with a non-French keyboard layout.
Text expansions match Vim's `:digraph` commands.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage

#### Lowercase Accents

| Keyword  | Replaced |
|  -----   |  -----   |
|   `e'`   |    é     |
| `` e` `` |    è     |
|   `e^`   |    ê     |
|   `e:`   |    ë     |
|   `o^`   |    ô     |
| `` a` `` |    à     |
|   `a^`   |    â     |
|   `i^`   |    î     |
|   `i:`   |    ï     |
| `` u` `` |    ù     |
|   `u^`   |    û     |
|   `u:`   |    ü     |
|   `oe`   |    œ     |
|   `ae`   |    æ     |
|   `y:`   |    ÿ     |
|   `c,`   |    ç     |

#### Uppercase Accents

| Keyword  | Replaced |
|  ----    |   ----   |
|   `E'`   |    É     |
| `` E` `` |    È     |
|   `E^`   |    Ê     |
|   `E:`   |    Ë     |
|   `O^`   |    Ô     |
| `` A` `` |    À     |
|   `A^`   |    Â     |
|   `I^`   |    Î     |
|   `I:`   |    Ï     |
| `` U` `` |    Ù     |
|   `U^`   |    Û     |
|   `U:`   |    Ü     |
|   `OE`   |    Œ     |
|   `AE`   |    Æ     |
|   `Y:`   |    Ÿ     |
|   `C,`   |    Ç     |
