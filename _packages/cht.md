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
# espanso-package-cht

An espanso package for getting code snippets from [Igor Chubin's](https://github.com/chubin) console-oriented cheat sheet service [cht.sh](https://cht.sh). [Espanso](https://espanso.org/) is a free cross-platform text expander written in Rust.

![usage](https://github.com/bradyjoslin/espanso-package-cht/raw/master/images/chtjs.gif)

For more information about espanso packages, read the [documentation](https://espanso.org/docs/).

## Usage

Available replacements:

| replacement      | description                 |
| ---------------- | --------------------------- |
| `:cht/{query}/`  | Code only, no comments.     |
| `:vcht/{query}/` | Verbose. Code and comments. |

Uses [passive replacement](https://espanso.org/docs/passive-mode/), so it is triggered by highlighting the text and double tapping your configured passive key.

## Installation

`espanso install cht https://github.com/bradyjoslin/espanso-package-cht --external`

## Dependencies

Passive replacement should be enabled in the espanso `default.yml` configuration file:

```yaml
enable_passive: true
passive_key: CTRL
```

Requires `curl`.

## Package Details

Repository: [https://github.com/bradyjoslin/espanso-package-cht/](https://github.com/bradyjoslin/espanso-package-cht/)


