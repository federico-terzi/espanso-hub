---
package_name: "kaimoji"
package_title: "Kaimoji"
package_desc: "A package providing Kaimoji expansions"
package_version: "0.1.0"
package_author: "Ian Pringle"
package_original_repo: "https://github.com/pard68/kaimoji"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A package providing Kaimoji expansions.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

