# EECS 201 HW 4
uniqname:  mayakh

## Question 1a
``` 1a
To indent the current line, you can use ==, to indent all lines below you can use =G, and to index the entire file use gg=G.
```

## Question 1b
``` 1b
To indent a block of code, go to one of the braces and use the =% commmand.
```

## Question 2
``` 2
To split the window, use :split. Can then use Ctrl+W to switch to that window. Then can :split filename to split to a particular file.
```

## Question 3
``` 3
After using :make, can use :cwindow to bring up window with all errors in a list. :cn, jumps to next error automatically, while :cp, goes to previous error. :copen opens up a quickfix window.
```

## Question 4
``` 4
To comment large block of python code in Vim, go to first column of first line you want to comment, press ctrl+V to select lines you want to comment. Then, press shift, I, #, space. Then press Esc.
```

## Question 5
``` 5
To create a macro, choose a register to record into(a-z), then begin recording with q command, type your register, edit however you want, then end recording with q command. To replay macros use @register. 
```

## Question 6a
``` 6a
To jump to a matching bracket, the % key can be used. 
```

## Question 6b
``` 6b
To run a shell command in vim, you can use :!ls.
```

## Question 7
``` 7
Error in opening display: (gedit:7739): Gtk-WARNING **: 16:33:23.890: cannot open display:
```

## Question 8
``` 8
Can suspend gedit with ctrl+z, and background it by using bg command. 
```

## Question 9
``` 9
In order to launch gedit so that you can still use the terminal, can start like gedit &
```
