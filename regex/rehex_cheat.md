basics:
* Match preceding character 0 or more times
+ Match preceding character 1 or more times
. Match any single character
x|y Match either 'x' or 'y'
\ Escape a special character
b The character b
abc The string abc

Character Classes I
\dMatch a digit character
\DMatch a non-digit character
\sMatch a single white space character (space, tab, form feed, or line feed)
\SMatch a single character other than white space
\wMatch any alphanumeric character (including underscore)
\WMatch any non-word character
Character Classes II
[abc]Match any one of the characters in the set 'abc'
[^abc]Match anything not in character set 'abc'
[\b]Match a backspace
Assertions
^Match beginning of input
$Match end of input
\bMatch a word boundary
\BMatch a non-word boundary
?=Lookahead
?!Negative lookahead
Assertions II
?<=Lookbehind
?<!Negative lookbehind
?>Once-only subexpression
?()If then condition
?()|If then else condition
?#Comment
Quantifiers
{n}Match exactly n occurrences of preceding character
{n,m}Match at least n and at most m occurrences of the preceding character
?Match 0 or 1
Special Characters I
\cXMatch control character X in a string
\nMatch a line feed
\rMatch a carriage return
\tMatch a tab
\0Match a NULL
Special Characters II
\fMatch a form feed
\vMatch a vertical tab
\xhhMatch character with code hh (2 hex digits)
\uhhhhMatch character with code hhhh (4 hex digits)
Flags
gGlobal search
iCase-insensitive search
mMulti-line search
y"sticky" search match starting at current position in target string
Groups
(x)Match 'x' and remember the match
(?:x)Match 'x' but do not remember the match
\nA back reference to the last substring matching the n parenthetical in the regex
