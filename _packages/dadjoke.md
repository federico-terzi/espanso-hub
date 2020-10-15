---
package_name: "dadjoke"
package_title: "Dadjoke"
package_desc: "A random dad joke every time"
package_version: "0.1.0"
package_author: "Yordan Ivanov"
package_original_repo: "https://github.com/ivanovyordan/espanso-package-dadjoke"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A simple package that expands to a random dad joke every time.

Powered by [icanhazdadjoke](https://icanhazdadjoke.com/).

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage 

Simply type `:dadjoke` and it will be replaced by a random dad joke.

## Prerequisites

* Active Internet connection
* `curl`

### Note

* Not tested on Windows
