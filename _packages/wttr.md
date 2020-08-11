---
package_name: "wttr"
package_title: "wttr Package"
package_desc: "A package to get the weather from wttr.in."
package_version: "0.1.0"
package_author: "Brady Joslin"
package_original_repo: "https://github.com/bradyjoslin/espanso-package-wttr"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---
# espanso-package-wttr

An espanso package for getting the weather from [Igor Chubin's](https://github.com/chubin) console-oriented weather service [wttr.in](https://wttr.in).

For more information about espanso packages, read the [documentation](https://espanso.org/docs/).

## Usage

Available replacement examples:

| replacement           | sample output                    | description                           |
| --------------------- | -------------------------------- | ------------------------------------- |
| `:wttrin`             | Spring, United States: ⛅️ +80°F | Current location's current weather    |
| `:moonphase`          | 🌕                               | Current phase of the moon             |
| `:wttrat/{location}/` | dallas: ☀️ +88°F                 | Current weather in specified location.  Separate words with `+` instead of spaces. |

`:wttrat` uses [passive replacement](https://espanso.org/docs/passive-mode/), so it is triggered by highlighting the text and double tapping your configured passive key.

## Installation

`espanso install wttr https://github.com/bradyjoslin/espanso-package-wttr --external`

## Dependencies

Passive replacement should be enabled in the espanso `default.yml` configuration file:

```yaml
enable_passive: true
passive_key: CTRL
```

Requires `curl`.

## Package Details

Repository: [https://github.com/bradyjoslin/espanso-package-wttr/](https://github.com/bradyjoslin/espanso-package-wttr/)

