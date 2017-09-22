yuidoc-cliqz-theme
======================

Based on [yuidoc-bootstrap-theme](https://www.npmjs.org/package/yuidoc-cliqz-theme)


When running yuidoc from command line:
    -t : themedir
    -H : helper js file

Example:

```
    yuidoc -t _location_/yuidoc-cliqz-theme -H _location_/yuidoc-cliqz-theme/helpers/helpers.js
```

When running with grunt it is best to use this as a submodule.

Then under yuidoc.json options add:

```
    "themedir" : _location_/yuidoc-cliqz-theme,
    "helpers" : [ _location_/yuidoc-cliqz-theme/helpers/helpers.js ]
```

Example:

```
    {
        "name": "Example",
        "url": "www.example.com",
        "version": "0.1.0",
        "options": {
            "paths": "_location to parse_",
            "outdir": "build/docs",
            "exclude": "lib,docs,build",
            "themedir": "_location_/yuidoc-cliqz-theme",
            "helpers": ["_location_/yuidoc-cliqz-theme/helpers/helpers.js"]
        }
    }
```
