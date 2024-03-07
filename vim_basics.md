### Modes :

- **cmd Mode :** is default & anything typed here acts as a cmd --> (Cursor naviagtion active)
- **Editor Mode :** actviates_by(i,a,o) key

### VIM Instructions

0. : instruction-to-editor(vim) <-- FORMAT
1. vi or vim or nano file.txt = open a file in editor, @bottom file-name & its path is displayed.
2. i,a,o = press any to edtor in editor mode
3. Esc : press Esc-btn to exit editor mode i.e. back to cmd mode --> (Cursor naviagtion active)

4. :w = Save i.e. write
5. :wq or :wq! = save & quit i.e. write quit
6. :w file-name = save as
7. :w! = Save & write to non-writable file
8. :q = quit
9. :q! or !q = quit & discard
10. ZZ = save & quit

### Naviagtion

j = Down
k = Up
h = left
l = right

G = goto last line of file --> jump lines
i = start typing before current char
I = start typing @begning of current char
a = start typing @after of current char
A = start typing @end of current char
O = start typing on a new line before current line
o = start typing on a new line after current line

0 = bring @start of current line
^ = bring @start of current line
$ = bring @end of current line
d0 = del till start of current line
d$ = del till end of current line

### Del

x = del current char
X = del char before cursor
r = replace current char e.g. A* is char having cursor & type B , replace A by B
xp = switch 2 chars
D = del line form current char A*..... to the end of line
dG = del from current line to eof

### Undo | Repeat

u = undo last cmd
. = repeat

### Copy | Paste | Cut

yy = copy a line
p = paste after current line
P = paste before current line
ndd = cut (specify n) num of lines or del
nyy = copy (specify n) num of lines

### JOIN lines

j = join 2 lines
yyp = repeat current line
ddp = swap 2 lines

### Move Fwd, Bwd,

w = fwd
b = bwd
nw = move specifed num of words
dw = del one word
yw = copy one word
ndw = del specified num of words

### Search Str

/str = fwd search
?str = wd search
/^str = fwd serach @begning of line
/str$ = fwd serach @begning of line
n = goto nxt occurence
/\he\ = search for 'he' word & not sub-str
/pl[xyz]ce = search for str begins with 'pl' followed by any chars & ends with 'ce'

### Replace (all)

:statr-line, endline, s/old-str/new-str/g
