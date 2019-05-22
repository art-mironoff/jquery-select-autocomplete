jQuery-selectAutocomplete
===================

A lightweight completion suggester plugin for jQuery.

Compatible with jQuery 1.8.0+. No dependencies except the jQuery library.
Released under the MIT License: http://www.opensource.org/licenses/mit-license.php

# Example
https://art-mironoff.github.io/jQuery-selectAutocomplete/example.html

# Usage

```javascript
var data = [
  { id: "1", name: "ActionScript" },
  { id: "2", name: "AppleScript" },
  { id: "3", name: "Asp" }
];
$("#autocomplete").selectAutocomplete({
  // Available options with defaults:
  cancelButtonText: "Remove",
  data: data,
  dropdownAttrs: {
    class: "dropdown"
  },
  minLength: 3,
  onSelect: function(e, id, value) {
  },
  onCancel: function (e) {
  },
  showCancelButton: true,
  wrapperAttrs: {
    class: "select-autocomplete"
  }
});
```

```html
<input id="autocomplete" type="text" name="search" />
```
