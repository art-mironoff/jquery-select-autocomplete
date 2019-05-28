jQuery-selectAutocomplete
===================

A lightweight completion suggester plugin for jQuery.

Compatible with jQuery 1.8.0+. No dependencies except the jQuery library.
Released under the MIT License: http://www.opensource.org/licenses/mit-license.php

# Example
https://art-mironoff.github.io/jquery-select-autocomplete/example.html

# Usage

```javascript
var data = [
  { id: "1", name: "ActionScript" },
  { id: "2", name: "AppleScript" },
  { id: "3", name: "Asp" }
];

$("#autocomplete").selectAutocomplete({
  data: data
});
```

```html
<input id="autocomplete" type="text" name="search" />
```

# Props
| Key              | Default                          | Type   |
|------------------|----------------------------------|----------|
| cancelButtonText | "Remove"                         | String   |
| data             | [ ]                              | Array    |
| dropdownAttrs    | { class: "dropdown" }            | Object   |
| minLength        | 3                                | Integer  |
| onSelect         | function { }                     | Function |
| onCancel         | function { }                     | Function |
| showCancelButton | true                             | Boolean  |
| wrapperAttrs     | { class: "select-autocomplete" } | Object   |

To specify settings after the init, use this syntax:
```javascript
$("#autocomplete").selectAutocomplete({
  cancelButtonText: "Remove",
  data: [],
  dropdownAttrs: {
    class: "dropdown"
  }
});
```
