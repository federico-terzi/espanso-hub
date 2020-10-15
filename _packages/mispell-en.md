---
package_name: "misspell-en"
package_title: "Misspell EN"
package_desc: "Replace commonly misspelled english words."
package_version: "0.1.2"
package_author: "Timo Runge"
package_repo: "https://github.com/timorunge/espanso-misspell-en"
is_core: false
---

# {{ page.package_title }}

misspell-en is a espanso package which is replacing commonly misspelled english words.
The package is based on [github.com/client9/misspell](https://github.com/client9/misspell).

## Usage

Type `yuo` and see what's happening.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

Repository: <{{ page.package_original_repo }}>

## License

[BSD 3-Clause "New" or "Revised" License](https://github.com/timorunge/espanso-misspell-en/blob/master/LICENSE)

Misspell is [MIT](https://github.com/client9/misspell/blob/master/LICENSE).
