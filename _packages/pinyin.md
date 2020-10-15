---
package_name: "pinyin"
package_title: "Pinyin"
package_desc: "Pinyin vowels"
package_version: "0.1.0"
package_author: "Jordan Matelsky"
package_original_repo: "https://github.com/j6k4m8/espanso-pinyin"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A package that adds support for easily typing [Pinyin](https://en.wikipedia.org/wiki/Pinyin) Mandarin Romanization characters. Transcribing the tones involve adding diacritics above vowels. This is difficult with a conventional QWERTY keyboard, and so this espanso package adds easy mnemonic support to type tones.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Usage

The mnemonic is:

* Type the vowel character
* Press <kbd>SHIFT</kbd>
* Type the "backslash" <kbd>\\</kbd> character
* Type the number of the tone you wish to add (e.g. 3)
* Release <kbd>SHIFT</kbd>

For example, to type `ě`, type <kbd>e</kbd>, <kbd>shift<kbd>\\</kbd><kbd>3</kbd></kbd>

| Character | Shortcut |
|---|-------|
| ā | `a\|!` |
| á | `a\|@` |
| ǎ | `a\|#` |
| à | `a\|$` |
| ē | `e\|!` |
| é | `e\|@` |
| ě | `e\|#` |
| è | `e\|$` |
| ī | `i\|!` |
| í | `i\|@` |
| ì | `i\|$` |
| ǐ | `i\|#` |
| ō | `o\|!` |
| ó | `o\|@` |
| ǒ | `o\|#` |
| ò | `o\|$` |
| ū | `u\|!` |
| ú | `u\|@` |
| ǔ | `u\|#` |
| ù | `u\|$` |
| ǖ | `u:\|!` |
| ǘ | `u:\|@` |
| ǚ | `u:\|#` |
| ǜ | `u:\|$` |
