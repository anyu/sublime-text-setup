sublime-text-setup
==================

Plugins
--------------
- Package Control: http://wbond.net/sublime_packages/package_control
- Emmet: https://github.com/sergeche/emmet-sublime
- AdvancedNewFile: https://github.com/skuroda/Sublime-AdvancedNewFile
- Side Bar: https://github.com/titoBouzout/SideBarEnhancements
- SublimeCodeIntel: https://github.com/Kronuz/SublimeCodeIntel
- ColorPicker: https://github.com/weslly/ColorPicker

Shortcuts
--------------
**Files**
cmd+shift+p    // Bring up ST command palette
cmd+shift+t    // Bring up last closed tab
cmd+t          // Jump to file in project
cmd+n          // Create new file in project
cmd+shift+n    // Open new file in new window
ctrl+`         // Open ST2 console

**Moving around**
cmd+shift+right arrow     // Highlight rest of line
cmd+left/right arrow      // Move to beginning/end of line
cmd+shift+d               // Duplicate selection
option+cmd+click          // Multi-line edit

Other
--------------
**Bracket highlighting**

Preferences -> Browse packages -> Color Scheme - Default find out your current theme file (default's Monokai.tmTheme). 
Open it using Sublime Text and find the following part:

<key>bracketsForeground</key>
<string>#F8F8F2A5</string>
<key>bracketsOptions</key>
<string>underline</string>

<key>bracketContentsForeground</key>
<string>#F8F8F2A5</string>
<key>bracketContentsOptions</key>
<string>underline</string>

Change to the following to remove underline & add orange color to brackets

<key>bracketsForeground</key>
<string>#FF8000</string>
<key>bracketsOptions</key>
<string>foreground</string>

<key>bracketContentsForeground</key>
<string>#FF8000</string>
<key>bracketContentsOptions</key>
<string>foreground</string>
