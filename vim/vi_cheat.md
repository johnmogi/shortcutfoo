hi

Beginner Text Navigation:
k Move up one line
j Move down one line
h Move left one character
l Move right one character
e Move to end of word
b Move to beginning of word
$ Move to end of line
0 Move to beginning of line
H Move to first line of screen
M Move to middle line of screen
L Move to last line of screen
w Move to next word
b Move to previous word

Beginner Text Editing
ce Change rest of current word
dw Delete word
i Insert
I Insert at start of line
a Append
A Append at end of line
o Insert new line below
O Insert new line above
r Change char and return to cmd mode
R Enter replace mode
ESC Exit insert mode to normal mode

Intermediate Text Navigation I
fw Move to next 'w' on line
Fw Move to previous 'w' on line
tw Move before next 'w' on line
Tw Move before previous 'w' on line
; Repeat last f, F, t, or T
, Repeat last f, F, t, or T reversed
5j Move down 5 lines
5k Move up 5 lines
Intermediate Text Navigation II
5w Move 5 words forward
5b Move 5 words backward
ctrl+e Scroll down
ctrl+y Scroll up
gg Go to beginning of file
G Go to end of file
12G Go to line 12
ctrl+f Move forward one screen
ctrl+b Move backward one screen
Intermediate Text Editing I
yy Yank (copy) line
y$ Yank (copy) to end of line
ye Yank (copy) to end of word
dd Delete (cut) current line
5dd Delete 5 lines
d2w Delete (cut) next two words
D Delete (cut) to end of line (one char)
p Paste
Intermediate Text Editing II
P Paste before cursor
u Undo
U Undo all changes to current line
ctrl+r Redo
. Repeat last change
5. Repeat last change 5 times
de Delete (cut) to end of word
d$ Delete (cut) to end of line
Advanced Text Navigation
^ Move to first non whitespace char
20| Go to column 20
% Go to matching parenthesis or bracket
ctrl+o Move to older position
ctrl+i Move to newer position
zt Scroll current line to top of window
Visual Mode
:w filename↵ Write selection to 'filename'
v Visual mode select characters
V Visual mode highlight lines
~ Swap case
> Shift right
< Shift left
c Change highlighted text
y Yank (copy) highlighted text
d Cut highlighted text
= Re-indent selection
Window Management
:e filename↵ Set current buffer to 'filename'
:sp↵ New window above
:vs↵ New window to left
:q↵ Close current window
:qa↵ Close all windows
File Management
:q!↵ Quit without saving
:wq↵ Save and exit
:x↵ Save and exit if modified
:r filename↵ Read and insert 'filename'
:r !cmd↵ Execute and insert results of 'cmd'
:!rm filename↵ Delete 'filename'
:e↵ Open new file
ctrl+g Show file info
ga Show character info
:w↵ Save changes
:q↵ Quit
Bookmarks
:marks↵ Show bookmarks
ma Mark position 'a'
`a Go to bookmark position 'a'
`` Go to previous position
Replace
:s/foo/bar↵ Replace first 'foo' with 'bar' on line
:s/foo/bar/g↵ Replace all 'foo' with 'bar' on line
:%s/foo/bar/g↵ Replace all 'foo' with 'bar' in file
:%s/foo/bar↵ Replace first 'foo' with 'bar' on every line
:s/foo/bar/gc↵ Confirm replace all 'foo' with 'bar' on line
:s/foo/bar/i↵ Ignore case replace first 'foo' with 'bar'
rx Replace current char with 'x'
:%s/foo/bar/gc↵ Confirm replace all 'foo' with 'bar' in file
:2,9s/foo/bar/g↵ Replace all 'foo' with 'bar' between lines 2 and 9
Search
/foo↵ Search forwards for 'foo'
?foo↵ Search backwards for 'foo'
n Search next
N Search previous
* Search for current word forward
:set nois↵ Turn off incremental search
:set ic↵ Set ignore case
:set is↵ Set incremental search
:set hls↵ Set highlight matching phrases
Misc
vim -t foo↵ Start editing where foo is defined
:help cmd↵ Lookup 'cmd' in help
:make↵ Run make
:!ls↵ Execute 'ls' command
ctrl+p Move autocomplete backward
ctrl+x Move language autocomplete forward
ctrl+o Move language autocomplete backward
K Look up word in man pages
yw Yank to beginning of next word