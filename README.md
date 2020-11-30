# vscode-settings


## Settings

`settings.json` is the global settings file for VSCode.

On OSX, it lives somewhere like `~/Library/Application\ Support/Code/User/settings.json`


## Snippets

The `snippets` folder can contain snippets for various lanaguages.

On OSX, it lives somewhere like `~/Library/Application\ Support/Code/User/snippets`


## Cheatsheat

These are some keyboard shortcuts I find helpful (OSX):

``` bash
cmd shift p     command palette (search for anything!)
cmd p           search for file
ctrl r          search recent (useful for switching workspaces)

cmd b           toggle sidebar

cmd n           New file
cmd o           open - could be a directory or whatever
cmd k           Keep file open (by default, files openned by jumping are closed automaticaly on jumping elsewhere)
cmd k o         open current file in a new window
ctrl tab        jump between currently open files

cmd 0           move focus to the explorer (then cmd+1 to move back to code)
cmd \           split screen (then cmd+1, cmd+2 etc to switch between)

cmd-shift-o     outline - quick way of navigating around code

ctrl g          go to line

ctrl -          jump back to previous edit position
ctrl shift -    jump to next edit position

cmd alt s       save all

cmd f           find (then enter / shift-enter or cmd-g / shift-cmd-g for prev/next)
cmd shift f     find in all files (then F4 / shift F4 for prev/next)
alt cmd f       replace
alt shift cmd f replace in all files
cmd t           find symbol (searches whole project for something)

alt F12         peek definition
F12             jump to definition (then c-minus to get back, or cmd-w to close the tab)
alt shift F12   find all refs
shift F12       peek all refs

F2              rename (refactor)
shift F2        rename all

ctrl shift left/right   expand to select region
cmd alt up/dn           multiple cursors (or alt-click for differnt lines)

shift alt o     organise imports

(for snippets)  search the cmd shift p

regex groups    (xxx)  // then can access in replace with $1 $2 etc
                i.e. wrap each line in quotes from when text starts:
                       find:    ( *)(.*)
                       replace: $1"$2",
                NOTE: if there is a selection, the replace starts AFTER that selection
                      SO... just put the cursor, NO SELECTION!
                      OR... make sure hamburger-text icon in regex is enabled

multiple cursors   alt-click (or alt-cmd-up or alt-cmd-down )

F8                 Show error detail (super useful!)
```