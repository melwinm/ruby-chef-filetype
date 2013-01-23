Ruby and Chef filetype for JetBrains IDE's
==========================================

Gives you:
----------
* code highlighting 
* flat codecompletion (no structure logic)
* tested with JetBrains PHPStorm 5

Installation:
-------------
* exit your IDE
* copy **ruby_chef_file.xml** into "[WinUserDir]/.WebIde[Version]/config/filetypes"
* open file "[WinUserDir]/.WebIde[Version]/config/options/filetypes.xml" and copy the following lines in the \<extensionMap> element.
* start your IDE

```xml
<mapping ext="rb" type="ruby_chef_files" />
<mapping ext="erb" type="ruby_chef_files" />
```
