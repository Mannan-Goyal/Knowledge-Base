# Vim Keybinds Cheatsheet 

```
- h      : to move left
- j      : to move down
- k      : to move up
- l      : to move right
- G      : to move to the end of file
- gg     : to move to top pf the file
- Esc    : switch to normal/command mode
- i      : switch to insert mode
- {      : navigate up in codeblocks
- }      : navigate down in codeblocks
- dd     : delete a line and put it in clipboard
- u      : to undo
- ctrl+r : redo
- yy     : copy line
- p      : paste below
- P      : paste above
- V      : enter visual mode
- v      : visual mode but you can select indivisual character
- o      : drops you down 1 line and puts in insert mode
- O      : puts you up one line and puts you in insert mode
- w      : takes you to the next word
- b      : takes you to the previous word
- :[n] : takes you to the nth line
- 0      : takes you to the absolute beginning of the line
- ^      : takes you to the first word in the line (0w can also be used to emulate the same behaviour)
- $      : takes you to the end of the line 
- W      : takes you to the next space in the line
- B      : takes you to the prev space in the line
- t[char]: takes you 1 char before first occurence of that char
- f[char]: takes you to the first occurence of that char
  - ;       : can be used to navigate to the next instance of the character for both t and f
- %      : helps you to switch between starting and ending of a opening/closing signifier
- c      : to change a word
  - cw      : c used in conjuntion with w to signify change word
  - dw      : delete word
  - ct[char]: if you want to replace the sentence till some char
  - dt[char]: if you want to delete the sentence till some char
- D      : delete till the end of the line from the position of the cursor
- zz     : used to bring your cursor and the line that it is on to the center of the screen
- a      : moves one to the right and puts you in insert mode
- A      : moves you to the end of the line and puts you in insert mode
- x      : deletes what you r cursor is hightlighting without exiting command mode 
- I      : takes you into insert mode at the beginning of the line
- ~      : used to change case of the highlighted characters
- .      : redo the last command that you did (very powerful) 
- R      : used to write over whatever is written
- r      : can be used to write over a single highlighted character
- </>    : to indent or unindent code
- Macros
  - q      : start recording the macro
  - [key]  : press the key you want to store the macro in
  - q      : press q again to stop recording the macro
  - @[KEY] : press @[SHIFT+key] to replay the macro you recorded
- ctrl+v : select code block wise, can be used to produce multiple cursors with I/i
- /<text>: search for that text in the file  
```

## Notes: 
- You can put numbers ib front of almost all commands eg. 20j will take you down 20 lines.
- This cheatsheet is made on the basisi of the amazing [tutorial](https://www.youtube.com/watch?v=IiwGbcd8S7I) by Ben Awad.
