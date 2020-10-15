---
package_name: "italian-accents"
package_title: "Italian Accents"
package_desc: "Include Italian accents substitutions to espanso."
package_version: "0.1.0"
package_author: "Federico Terzi"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A simple package to conveniently type italian with a non-italian keyboard layout.
It works by replacing keywords like `e'` with `è`. More details below.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

### Usage

This package replaces the following keywords with the associated accent while you're
typing:

#### Lowercase Accents

Keyword | Replaced
--- | ---
`e'` | è
`e//` | é
`i'` | ì
`a'` | à
`o'` | ò
`u'` | ù

#### Uppercase Accents

Keyword | Replaced
--- | ---
`E'` | È
`E//` | É
