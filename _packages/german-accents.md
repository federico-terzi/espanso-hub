---
package_name: "german-accents"
package_title: "German accents"
package_desc: "Include German Accents substitutions to espanso"
package_version: "0.1.0"
package_author: "Puvendran Pillay"
package_original_repo: "https://github.com/puven12/espanso-german-accents"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A simple package to conveniently type german with a non-german keyboard layout.
It works by replacing keywords like `a"` with `ä`. More details below.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage

This package replaces the following keywords with the associated accent while you're
typing:

#### Lowercase Accents

| Keyword | Replaced |
|  ----   |  ----    |
| `a"`    |  ä       |
| `o"`    |  ö       |
| `u"`    |  ü       |
| `s"`    |  ß       |

#### Uppercase Accents

| Keyword | Replaced |
|  ----   |  ----    |
| `A"`    |  Ä       |
| `O"`    |  Ö       |
| `U"`    |  Ü       |
