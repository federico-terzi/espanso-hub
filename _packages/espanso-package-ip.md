---
package_name: "ip"
package_title: "Public IP"
package_desc: "Insert your public IP address (Linux only)"
package_version: "0.1.0"
package_author: "Aurelien Bras"
package_original_repo: "https://github.com/profy12/espanso-package-ip"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A simple package to detect and insert your public ip.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage 

Type `:ip` and it will be replaced with your public IP address.

## Prerequisites

* `dig`

### Note

* This package was tested **only** on Linux.
