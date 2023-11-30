# Vim Cheat Sheet

| Command | Description |
| - | - |
| hjkl | Moving on file |
| w/b | Move word forward/back |
| :digit: | Do smoething n times |
| d | Verb delete |
| c | Verb substitute |
| 0 | Beggining of the line |
| $ | End of the line |
| ^ | First character of line |

## Find and Replace
| Command | Description |
| - | - |
| :s/foo/bar/ | Replace first ocurrence |
| :s/\<foo\>/bar/ | Replace whole word firs ocurrence |
| :s/foo/bar/g | All ocurrences on current line |
| :%s/foo/bar/g | All ocurrentes on file |
| :%s/foo/bar/gc | All ocurrentes on file with confirmation |
| :%s/foo/bar/gi | All ocurrentes on file ignoring case |
| :n,ms/foo/bar/g | All ocurrentes between line n and m |

<!---
R replace mode
--->
