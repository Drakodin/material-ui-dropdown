# material-ui-dropdown
Dropdown component built in the Material-UI style from existing components in core/lab/icons

## How to install
1. `git clone <repo-link>` and move the repository (minus the .git and etc.) into the project folder
2. Whenever I figure out (or someone else figures out) how to make an npm module from my source code.

## How to use

### Requirements
React 16.8 or higher, Bootstrap 4 (for styling reasons; you can always override this with custom css classes)

### Implementation
```
import Dropdown from 'material-ui-dropdown/Dropdown';
...
  return (
    ...
    <Dropdown *props go here*/>
    ...
  )
```

## Props (No docs at the moment)
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

## Sources/References
1. [Material UI](https://material-ui.com/)
2. [Bootstrap](https://getbootstrap.com/)
3. [React](https://reactjs.org/)

## Live on CodeSandbox
[![Edit mui-dropdown-csb](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/mui-dropdown-csb-rw7xz?fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark)
\* I don't have an account, I just needed a host.
