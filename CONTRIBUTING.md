# Contributing to calcite-sketch-libraries

You want to contribute? Nice! Below are some guidelines for ensuring that your contribution makes sense for everybody.

## ⚠ Reporting Issues

Found a problem?

See if your issue or idea has already been reported.
Provide detailed reproduction instructions as well as what behavior is expected.

## 📝 Adding or updating components?

Join the conversation on the Microsoft Teams under the appropriate platform:

**[Calcite team](https://teams.microsoft.com/l/team/19%3a3ce5ad449cba48958db154459f5a9a8f%40thread.skype/conversations?groupId=56fae21a-9407-4943-859f-a9bfcf0bbad3&tenantId=aee6e3c9-711e-4c7c-bd27-04f2307db20d)**


## 👓 Reviews

### Things to keep in mind when working on additions to a component library

- Sensible naming and organization of pages, artboards and symbols.
- Consistency in symbol naming, reusing patterns for symbol structure, ensuring no duplication of existing symbols and adequate overrides for customization.
- Symbol instances should usually be named the same as the symbol itself (minus it's path).
- Create an instance of the symbol - play with it, is the structure logical / easy to use? Does it respond appropriately when resized?

### Checklist for reviewing component library additions

- Instances of each symbol are on the Example page(s) in a variety of configurations and sizes.
- Symbol names follow existing patterns.
- Symbol names are unique.
- Symbols likely to be used at different fixed heights are built as multiple symbols (sharing overrides).
- Symbols respond to resizing correctly.
- Symbols support different insets (if applicable).
- Symbol overrides follow existing patterns (e.g. Inset, Left, Right, Color, etc.).
- Symbol override menus only contain options that make sense (make sure override symbol dimensions are unique).
- Symbols include padding and separators necessary for them to snap into correct placement relative to other elements.
- Symbol color overrides default to a generic button/link color instead of black or the tint color for a specific app.