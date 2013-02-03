Sublime Text 2 setup
==================

<b>Color Scheme:</b> Monokai Bright

Settings
--------------  
    // The number of spaces a tab is considered equal to
    "tab_size": 2,

    // Set to true to insert spaces when tab is pressed
    "translate_tabs_to_spaces": true,

Plugins
--------------
- Package Control: http://wbond.net/sublime_packages/package_control
- Emmet: https://github.com/sergeche/emmet-sublime
- AdvancedNewFile: https://github.com/skuroda/Sublime-AdvancedNewFile
- SideBarEnhancements: https://github.com/titoBouzout/SideBarEnhancements
- SublimeCodeIntel: https://github.com/Kronuz/SublimeCodeIntel
- ColorPicker: https://github.com/weslly/ColorPicker
- Markdown Preview: https://github.com/revolunet/sublimetext-markdown-preview

Shortcuts
--------------
**File Navigation**
- cmd+shift+p    // Bring up ST command palette
- cmd+shift+t    // Bring up last closed tab
- cmd+t          // Jump to file in project
- cmd+n          // Create new file in project
- cmd+shift+n    // Open new file in new window
- ctrl+`         // Open ST2 console
- cmd+k+b        // Toggle sidebar
- cmd+f          // Search in file
- cmd+shift+f    // Search in project
- cmd+option+2   // Split 2 column view
- cmd+option+1   // 1 column view
- ctrl+shift+2   // Move file to view 2
- ctrl+1         // Move cursor to view 1
- ctrl+2         // Move cursor to view 2
- ctrl+cmd+f     // Fullscreen mode


**Editing**
- cmd+l                     // select line
- cmd+shift+right arrow     // Highlight rest of line
- cmd+left/right arrow      // Move to beginning/end of line
- cmd+shift+d               // Duplicate selection
- option+cmd+click          // Multi-line edit
- cmd+k+u                   // Make selection uppercase
- cmd+k+l                   // Make selection lowercase
- ctrl+shift+k              // Delete from cursor to end of line
- cmd+k+backspace           // Delete from cusor to start of line
- cmd+enter                 // Insert line after
- cmd+shift+enter           // Insert line


Other
--------------

**Bracket highlighting**

<p>Preferences -> Browse packages -> Color Scheme - Default, find out your current theme. </p>
<p>Open and find the following part:</p>

    <key>bracketsForeground</key>
    <string>#F8F8F2A5</string>
    <key>bracketsOptions</key>
    <string>underline</string>
    
    <key>bracketcontentsforeground</key>
    <string>#F8F8F2A5</string>
    <key>bracketContentsOptions</key>
    <string>underline</string>`

Change to the following to remove underline & add orange color to brackets

    <key>bracketsForeground</key>
    <string>#FF8000</string>
    <key>bracketsOptions</key>
    <string>foreground</string>
    
    <key>bracketContentsForeground</key>
    <string>#FF8000</string>
    <key>bracketContentsOptions</key>
    <string>foreground</string>

Notes
--------------
- Default Settings will be overwritten upon updates; make changes to User Settings
