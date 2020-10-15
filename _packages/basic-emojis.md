---
package_name: "basic-emojis"
package_title: "Basic Emojis"
package_desc: "A package to include some basic emojis in espanso."
package_version: "0.1.0"
package_author: "Federico Terzi"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
featured: true
---

# {{ page.package_title }}

A simple package to bring basic emojis to espanso.
It works by replacing keywords like `:lol` with `😂`. More details below.

## Usage

This package replaces the following keywords with the associated emoji while you're
typing:

Keyword | Emoji
--- | ---
`:lol` | 😂
`:llol` | 😂😂😂😂
`:sad` | ☹
`:ssad` | ☹☹☹☹
`:sml` | 😊
`:strong` | 💪
`:stlol` | 💪😂
`:ba` | 😎
`:ok` | 👍
`:ook` | 👍👍👍👍
`:happy` | 😄
`:cry` | 😭
`:wow` | 😮

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

Repository: <{{ page.package_original_repo }}>
