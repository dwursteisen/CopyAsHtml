Copy As Html
=======

Copy of the source of the plugins [Copy As Html](http://plugins.intellij.net/plugin?pr=idea&pluginId=190)
The source comme from the archive of the [plugins](http://plugins.intellij.net/plugin/download?pr=idea&updateId=8720)

*I'm not the author of this plugins*

For more information, please check the plugin page from Jetbrains Plugins Repository :

[http://plugins.intellij.net/plugin?pr=idea&pluginId=190](http://plugins.intellij.net/plugin?pr=idea&pluginId=190)

Copies a snippet of code as html
-----
* Adds menu items "Copy as HTML" to main menu and editor popup. Will copy the current selection or the complete editor buffer. Currently only works if focus is in editor (for example won't work in project tree).
* Preserves more formatting than the built-in HTML export.
* HTML is only a snippet (without html and body tags) meant to be inserted into a complete HTML document.
* Currently HTML format is fixed and uses CSS a lot.
* Options: unindent, add border, padding, line numbers, tabs to spaces conversion, include editor's warning and error highlighting (see IDE Settings -> Copy as HTML).
* Reuses the editor "Show Line Numbers" setting (see Idea's "View" menu).