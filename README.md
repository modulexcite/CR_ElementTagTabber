'Element Tag Tabber' for CodeRush
===
This plugin allows you to use the existing TabToNextReference functionality to navigate between an open and close pair of tags.

Configuration
======
In addition to downloading and installing this plugin, you will need to adjust the context of the **Tab** and **Shift+Tab** shortcuts in order to make this work.

Here are the steps needed to achieve this:

  * DevExpress\Options (Or **Ctrl+Shift+Alt+O**)
  * IDE\Shortcuts
  * Navigation\References\NavFields
  * Highlight the **Tab** shortcut
  * Locate the **Editor\Code\InPairedHtmlElementNameTag**
  * Ensure that this context is ticked.
  * Repeat previous steps for the **Shift+Tab** shortcut

Usage
======
Place your caret on either the open or close tag of some HTML or XML and then hit Tab. Your caret will jump to the opposing tag ready for whatever additional work you wish to engage in. This can be particularly useful when navigating around large XML documents.

![](Screenshots/TTNR-HTML.gif)
