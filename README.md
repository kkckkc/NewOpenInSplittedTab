# Open in splitted tab

Note that this is a fork of [Open in splitted tab](https://github.com/parallaxe/OpenInSplittedTab) adding fixes
to make it work for Jetbrains IDEs from v2025.1 and onwards. It also adds the template gradle setup allowing GitHub actions 
builds etc.

AppCode plugin (also works in other Jetbrain-IDEs like IntelliJ, PhpStorm and so on) to open the
declaration/implementation of the current selected symbol within a vertically splitted tab. If there already is an
splitted tab (either vertically or horizontally), it will use this. Else it will open a new one. The intention was to
rebuild this functionality of the "assistant-editor" in Xcode.

![](OpenInSplittedTabPreview.gif)