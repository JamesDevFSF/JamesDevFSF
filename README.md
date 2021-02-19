- 👋 Hi, I’m @JamesDevFSF

Notes on sorting Flags with draggable UI:

✓ jQuery works - we can use sortable with nesting (see http://jsfiddle.net/validide/vzQ2X/1/), or a 3rd-party library to more easily serialize into a Nested Set model(can PHP-friendly parseString into Array https://webmobtuts.com/javascript/using-jquery-nestedsortable-plugin-to-sort-hierarchical-lists/), or enable minimizing (https://github.com/ilikenwf/nestedSortable). Depends on IE8/9 support requirements.

- Will check how sortable plays with onClick/manual list updates Monday, since we want modal "move" options to work seamlessly.
- Vue or React would avoid model-consistency errors but a little overkill for one UI element
