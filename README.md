# rowlow.settings.default

## Namespaces
Rowlow mixins, variables and functions are prefixed with `rowlow` perse. Generated css selectors however, are not prefixed by default. In order to to prefix them, you can overwrite a generic prefix variable ```$rowlow-namespace```. Every module, that generates css selectors will have a additional variable to set/overwrite specific namespaces, which will fallback to the ```$rowlow-namespace``` by default.

```
    $rowlow-namespace:          "rowlow-"; //set the generic namespace
    $rowlow-colors-namespace:   "rowlow-colors-"; //set a specific module namespace
``
