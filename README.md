# rowlow.settings.default

ROW LOW default settings hold important generic settings that can be overwritten depending on your needs.

## ```$rowlow-namespace```

ROW LOW's mixins, variables and functions are prefixed with ```rowlow-``` per se. Generated CSS selectors however, are not prefixed by default. In order to change this behavior, you can define a generic namespace that will be prefixed to any CSS selector using ```$rowlow-namespace```. Additionally, every ROW LOW module that is generating CSS selectors will have a additional variable to set a specific namespace. By default this specific namespace is equal to the generic namespace. Please look up the module's documentation for more details.

### Usage

```
    $rowlow-namespace: "rowlow-";
```
