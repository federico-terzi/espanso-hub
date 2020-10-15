---
package_name: "german-plz"
package_title: "German Postleitzahlen"
package_desc: "A package containing the german Postleitzahlen."
package_version: "0.1.1"
package_author: "Sascha F. Kraeling"
package_repo: "https://github.com/cyberfux/german-plz"
is_core: false
---

# {{ page.package_title }}

All german Postleitzahlen.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

View the [Repository]({{page.package_repo}}).
