---
package_name: "medical-docs"
package_title: "Medical Documentation"
package_desc: "A package to assist in medical Documentation"
package_version: "0.1.2"
package_author: "Bill Ressl"
package_original_repo: "https://github.com/wressl/medical-docs"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

Provides text expansion and templates to assist medical documentation.
The author is a practising family physician. So the original package is
targeted to family physicians, but should be general enough to help
anyone interested in medical documentation.

## Usage

Type the abbreviation, press space and it will be expanded to its corresponding expansion. For example, `bp` will be expanded to `blood pressure`.

You can find a list of available abbreviations and its expansions [here](https://github.com/wressl/medical-docs/blob/master/README.md#usage).

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

Repository: <{{ page.package_original_repo }}>

## License

[GNU General Public License v3.0](https://github.com/wressl/medical-docs/blob/master/LICENSE)
