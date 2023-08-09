# DropdownExtension
Add a dropdown element to your HTML natively

## Usage
  Attribute Options
  * source = `url` (json or xml format) {name: value...}
  * multiple = allows for multiple selection
  * searchable = gives you a search bar in the dropdown
  ```html
  <dropdown-element id="myDropdown4" class="dropdown" source="./data.json" preIcon="link" searchable="" multiple="" title="External Multiple Searchable Dropdown" src="">
      <i class="material-icons dropdown-pre-icon noselect">link</i>
      <span class="dropdown-title noselect">External Dropdown</span>
      <i class="material-icons dropdown-button noselect">arrow_drop_down</i>
      <dropdown-content class="dropdown-content">
      </dropdown-content>
  </dropdown-element>
  ```
## Dropdown Input
Work in progress, does not work at the moment
