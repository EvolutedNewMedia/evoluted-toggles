# evoluted-toggles
A simple bower package, which can be easily used by frontend-template.

# Installation
If using a typical frontend-template, make sure you have a .bowerrc file containing:
```javascript
{
  "directory": "src/bower_components"
}
```

Either add the module to your list of dependancies in the bower.json file if you have one, then run bower update or otherwise:

```javascript
bower install --save evoluted-toggles
```

Note: The --save flag adds it to your bower.json dependencies.

# Structure
The file structure mirrors that of the frontend-template, but doesn't include any compiled CSS.

# Usage
```shell
bower install [package name]
```

This will install the package and dependencies into /src/bower_components, actually making use of the Sass/JS is a different story..