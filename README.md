# Bootstrap Fonts Complete (Tiny Creek fork)

###### This fork exists to update the PostCSS dependency to resolve a Dependabot alert.

A complete list of Bootstrap Fonts and their sources.

## Usage

``` js
var fonts = require('bootstrap-fonts-complete');

console.dir(fonts);
```

yields

``` json
{
    "monospace": {
        "category": "monospace",
        "lastModified": "2015-07-24",
        "version": "v1",
        "variants": {
            "italic": {
                "400": {
                    "local": [
                        "'Menlo Italic'",
                        "'Menlo-Italic'",
                        ...
                    ]
                },
                ...
            },
            ...
        }
    },
    ...
}
```
