---
package_name: "mac-symbols"
package_title: "Mac Symbols"
package_desc: "Display common Mac symbols like ⌘ and ⌥"
package_version: "0.1.1"
package_author: "Lifesign"
package_original_repo: "https://github.com/lifesign/espanso-mac-symbols"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A simple package to display common Mac symbols like ⌘ and ⌥, More details below

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

### Usage
This package replaces the following keywords with the associated mac symbols while you’re typing:

| Keyword | Replaced |
| --- | --- |
| `:cmd` | ⌘ |
| `:shift` | ⇧ |
| `:ctrl` | ⌃ |
| `:alt` | ⌥ |
| `:left` | ← |
| `:right` | → |
| `:up` | ↑ |
| `:down` | ↓ |
| `:caps_lock` | ⇪ |
| `:esc` | ⎋ |
| `:eject` | ⏏ |
| `:return` | ↵ |
| `:enter` | ⌅ |
| `:tab` | ⇥ |
| `:backtab` | ⇤ |
| `:pgup` | ⇞ |
| `:pgdown` | ⇟ |
| `:home` | ↖ |
| `:end` | ↘ |
| `:space` | ␣ |
| `:del` | ⌫ |
| `:fdel` | ⌦  |
