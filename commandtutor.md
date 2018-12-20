##  Vim Tutor Commands

|Commands|Description|
|---|---|
|n|to search for the same phrase again in forward direction|
|N|to search for the same phrase again in backward direction|
|o|opens a new line and puts in insert mode (lowercase)|
|O|puts in insert mode at the cursor position (uppercase)|
|ctrl+o|to go back where you come from|
|x|used for deleting a character|
|p|to paste the clipboard after the cursor|
|P|to paste the clipboard before the cursor|
|:q!|exits the editor without saving the changes made|
|r(a,b,c,..2,....)|replace a character at the cursor posiiton|
|R|to replace more than one character|
|:r (filename)|retrieves the contents of the specified file and puts below the cursor point|
|:r (external command)|retrieves the output of the external command|
|:s/old/new/|substitutes the given word with a new word at the cursor position|
|:s/old/new/g|substitutes all the occurences  of the word with new word at the particular line|
|:%s/old/new/g|changes every occurence of the string in the whole file|
|:%s/old/new/gc|prompts for substitution globally|
|:#i,#s/old/new/g|substitution takes place between the specified line numbers (#,#)|
|:set ic|tp ignore case in searching and substituting|
|:set hls|for highlighting partial matches in searches|
|:set is|highlights the first occurence of the matched pattern from the cursor|
|:set noic|cancels the ignore case option|
|:set nohls|to remove the highlighting option|
|u|undo changes for the word the cursor is position at|
|U|undo changes for the entire line|
|v|visual selelction operator, used for selecting text|
|v :w (filename)|selects text and writes into the specified file|
|:wq|saving and exiting a file|
|:w (filename)|writes the copy of current file to the specified file|
|#w(1,2,3)|to move the cursor to specified words forward|
|x|used for deleting a character|
|x|used for deleting a character|
|y|yank operator,used for copying text|
|yw|yank operator,used for copying word|
|/ (pattern)|searches for the specified pattern|
|/ (pattern) \c|used for ignoring case for specific search|
|:! (external command)|used for executing external command|
|%|used in paranthesis matching for the purpose of debugging|
|^|navigates to the beginning of the text of a particular line|
|0|navigates to the beginning of the line|
|$|navigates to the end of the text of the current line|
|? (pattern)|backward pattern search|
