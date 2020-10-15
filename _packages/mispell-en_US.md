---
package_name: "misspell-en_US"
package_title: "Misspell en_US"
package_desc: "Replace british english with american english."
package_version: "0.1.2"
package_author: "Timo Runge"
package_repo: "https://github.com/timorunge/espanso-misspell-en"
is_core: false
---

# {{ page.package_title }}

misspell-en_US is a espanso package which is replacing british english with american english.
The package is based on [github.com/client9/misspell](https://github.com/client9/misspell).

## Usage

Type `tyre` and see what's happening.

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
