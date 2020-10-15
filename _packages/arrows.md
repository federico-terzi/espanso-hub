---
package_name: "arrows"
package_title: "Arrows"
package_desc: "Useful arrows and dashes"
package_version: "0.1.0"
package_author: "Jordan Matelsky"
package_original_repo: "https://github.com/j6k4m8/espanso-arrows"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A simple package to add arrows and dashes

## Usage

| Symbol | Shortcut |
|--------|----------|
| —     | `\--`, `\mdash`, or `\emdash`    |
| –     | `\ndash` or `\endash`    |
| <200b> (zero-width space)    | `\zwsp`  |
| •     | `\bul`   |
| ✓    | `\check` |
| §     | `\\sect` (Two slashes to avoid collision with LaTeX)    |
| →     | `\rarrow`    |
| ←     | `\larrow`    |
| ↑     | `\uarrow`    |
| ↓     | `\darrow`    |
| ⟷     | `\lrarrow`   |

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

Repository: <{{ page.package_original_repo }}>
