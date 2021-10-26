# Usage
- remove original 'User' folder (usually located in `%AppData%\Sublime Text 3\Packages`)
- clone repository into new 'User' folder
- install Package Control
- restart Sublime Text

# Troubleshooting
- Some [sublemacspro](https://github.com/sublime-emacs/sublemacspro) keybinds don't work well along with [Origami](https://github.com/SublimeText/Origami)
  - edit the `Default (Windows).sublime-keymap` file inside `%AppData%\Sublime Text 3\Installed Packages\Origami.sublime-package`
  - remove/re-bind all the default keybinds
  - pack the file