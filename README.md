idea-ruby-chef-filetype
=======================

Gives you:
----------
* code highlighting 
* flat codecompletion (no structure logic)
* tested with IDEA PHPStorm 5

Installation:
-------------
* exit your IDEA IDE
* copy **ruby_chef_file.xml** into "[WinUserDir]/.WebIde[Version]/config/filetypes"
* open file "[WinUserDir]/.WebIde[Version]/config/options/filetypes.xml" and copy the following lines in the \<extensionMap> element.
* start your IDEA IDE

```xml
<mapping ext="rb" type="ruby_chef_files" />
<mapping ext="erb" type="ruby_chef_files" />
```
