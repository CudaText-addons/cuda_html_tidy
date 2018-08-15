CudaText plugin to integrate HTML Tidy program.
HTML Tidy is a program, which helps to find errors in HTML documents and to perform some actions on HTML pages, such as "convert tags to lowercase", "convert document to XHTML form", "make document clean", "reformat for better readability" etc.

- Windows: plugin includes 32-bit program Tidy.exe
- Unix: you must install "tidy" package in your OS

Plugin adds menu items to "Plugins" menu:
- "Menu": shows list of configured Tidy actions. Each action formats source file, if it's ok; if not it shows error report in Validation tab of bottom panel.
- "Validate document": shows list of errors in code in Validation tab of bottom panel. You can double-click lines in this list to go to source code.
- "Browse configs": shows folder with config files, one txt file per Tidy action, you can edit configs or add new ones.

Help links:
- http://tidy.sourceforge.net/docs/quickref.html - HTML4 Tidy help
- http://w3c.github.io/tidy-html5/ - HTML5 Tidy help

Author: Alexey (CudaText)
License: MIT
