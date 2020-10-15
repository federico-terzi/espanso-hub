---
package_name: "belarusian-letters"
package_title: "Belarusian Letters"
package_desc: "Type belarusian letters without layout switching"
package_version: "0.1.0"
package_author: "Yaraslau Shapaval"
package_original_repo: "https://github.com/jahy/espanso-package-belarusian-letters"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

Type belarusian letters without layout switching

## Usage

| Keyword | Replaced |
|---------|----------|
| `У_`    | Ў        |
| `у_`    | ў        |
| `И_`    | І        |
| `и_`    | i        |
| `Г_`    | Ґ        |
| `г_`    | ґ        |

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

Repository: <{{ page.package_original_repo }}>
