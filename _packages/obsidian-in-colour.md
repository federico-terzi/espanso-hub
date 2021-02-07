---
package_name: "obsidian-in-colour"
package_title: "Obsidian in colour"
package_desc: "Makes the process of adding colour to Obsidian a tad bit easier."
package_version: "0.1.0"
package_author: "Karlo Miličić"
package_repo: "https://github.com/KuSi833/espanso-obsidian-in-colour"
is_core: false
---
# Obsidian in Colour

This package is meant to work in combination with Obsidian - the application for note taking.

## Functionality:

![demo](https://github.com/KuSi833/espanso-obsidian-in-colour/raw/master/oic_demo.gif)

Query is activated by the keyword `:col `, after which the user is asked for a colour and a text size using espanso forms.

The colour and size are then looked up in a local dictionary, if there is a match the property is replaced with the corresponding value. If no match is found the form inputs are left as is. 
This is useful for colour if one might want to use a specific value.

The dictionaries can be found in the python file "obsidian_colour.py", which every user should customise to their own needs.

## Installation
Make sure you have already installed [Espanso](https://espanso.org/install/) first.
```
espanso install obsidian-in-colour
espanso restart
```
Make sure to create a `scripts` directory in the `espanso` directory and store the **obsidian_colour.py** script there.
