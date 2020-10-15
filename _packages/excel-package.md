---
package_name: "excel-package"
package_title: "Excel"
package_desc: "Useful Excel formulas"
package_version: "1.0.0"
package_author: "Ali Karbassi"
package_original_repo: "https://github.com/karbassi/espanso-package-excel"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

Useful Excel formulas

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```
