---
package_name: "sharewifi"
package_title: "sharewifi"
package_desc: "An espanso package for quickly sharing Wi-Fi passwords and connection details on macOS."
package_version: "0.1.0"
package_author: "Brady Joslin"
package_original_repo: "https://github.com/bradyjoslin/espanso-package-sharewifi"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

An espanso package for quickly sharing Wi-Fi passwords and connection details on macOS using [sharewifi](https://github.com/bradyjoslin/sharewifi). Generates QR codes that auto-configure iOS and Android devices.

![sharewifi](https://github.com/bradyjoslin/espanso-package-sharewifi/raw/master/images/sharewifi.gif)

## Usage

| Replacement    | Description                                                  |
| -------------- | ------------------------------------------------------------ |
| `:sharewifi`   | Prints Wi-Fi password.                                       |
| `:qrsharewifi` | Prints Wi-Fi Network config QR Code for Android and iOS 11+. |
| `:vsharewifi`  | Verbose output. Prints SSID and Password.                    |

For proper formatting of qr codes when using `:qrsharewifi`, trigger the replacement in a plain text editor.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Prerequisites

* sharewifi - https://github.com/bradyjoslin/sharewifi

## Package Details

Repository: <{{ page.package_original_repo }}>
