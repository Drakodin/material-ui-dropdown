# material-ui-dropdown
Dropdown component built in the Material-UI style from existing components in core/lab/icons

## How to install
1. `git clone <repo-link>` and move the repository's subfolders (minus the .git and etc.) into the project folder
2. Whenever I figure out (or someone else figures out) how to make an npm module from my source code.

## How to use

### Requirements
React 16.8 or higher, Bootstrap 4 (A bootstrap flex-box class is attached to the base of the Dropdown; this may change in the future to remove this dependency)

### Implementation
```
import Dropdown from './dropdown/Dropdown';
// Or do "import { Dropdown } from './dropdown';
...
  return (
    ...
    <Dropdown *props go here*/>
    ...
  )
```

## Props
- **anchorEl**: *Node*; Anchor element of the DropdownList
- **listItemSrc**: *Array*; Array of elements that will populate the DropdownList
- **open**: *Boolean*; Determines whether or not the DropdownList is visible.
- **target**: *Array*; Source to store the values of the checkboxes (controlled input)
- **label**: *String*; Label to display inside the Dropdown

### Functions
- **listOnClick**: *Function*; Handles click event on checkbox/list items in DropdownList
- **onClose**: *Function*; Handles onClose event of DropdownList
- **onClick**: *Function*; Handles onClick event when clicking on the div itself, or the IconButton

### CSS
- **boxStyle**: CSS; In-line-styles for the ListItem components
- **dropStyle**: CSS; In-line-styles for the DropdownList component
- **listStyle**: CSS; In-line-styles to be applied to the List component
- **variant**: *String*; Current variants are default, light, and dark. They can be overrided like normal CSS w/o the need for Material's `classes` prop.

## Sources/References
1. [Material UI](https://material-ui.com/)
2. [Bootstrap](https://getbootstrap.com/)
3. [React](https://reactjs.org/)

## Live Demos
**Website**

[Dropdown w/ variants](https://drakodin.github.io/#/projects/mui-dropdown)
