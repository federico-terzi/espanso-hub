---
package_name: "shruggie"
package_title: "Shruggie"
package_desc: "Display the text emoticon ¯\\_(ツ)_/¯ AKA the Shruggie"
package_version: "0.1.0"
package_author: "Spike Ilacqua"
package_original_repo: "https://github.com/spikex/shruggie"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
featured: true
---

# {{ page.package_title }}

This package inserts ¯\\_(ツ)_/¯ (the Shruggie) when you type `:shrug`.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage

Type `:shrug`, get ¯\\_(ツ)_/¯

## Package Details

Repository: <{{ page.package_original_repo }}>
