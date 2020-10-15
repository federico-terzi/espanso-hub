---
package_name: "cht"
package_title: "cht Package"
package_desc: "A package to get the code snippets from cht.sh."
package_version: "0.1.0"
package_author: "Brady Joslin"
package_original_repo: "https://github.com/bradyjoslin/espanso-package-cht"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}


An espanso package for getting code snippets from [Igor Chubin's](https://github.com/chubin) console-oriented cheat sheet service [cht.sh](https://cht.sh).

![usage](https://github.com/bradyjoslin/espanso-package-cht/raw/master/images/chtjs.gif)

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage

Available replacements:

|   Trigger        | Description                 |
| ---------------- | --------------------------- |
| `:cht/{query}/`  | Code only, no comments.     |
| `:vcht/{query}/` | Verbose. Code and comments. |

Uses [passive mode](https://espanso.org/docs/passive-mode/), so it is triggered by highlighting the text and double tapping your configured passive key.

## Prerequisites

* Passive replacement should be enabled in the espanso `default.yml` configuration file:

    ```yaml
    enable_passive: true
    passive_key: CTRL
    ```
* `curl`

## Package Details

Repository: <{{ page.package_original_repo }}>
