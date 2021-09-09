# turbo-pascal-mac-shotcuts

## Description

This is a _Turbo Pascal Marcro Language_ file that adds current DOS/Mac-like Keyboard shortcuts to Borland's Turbo Pascal 7.0 IDE.

## How to install
- Go to the bin folder of your TP7 installation
- Run `TEMC.EXE MAC.TEM TURBO.TP`
- This will add the shortcuts to the (default) TURBO.TP settings file
- Afterwards the shortcuts will work, even though they will not be shown in the dropdown menus

## Why?
Because I found old Pascal programs of mine and using the IDE was a neat but pain. So I decided to fix it.


## Shortcuts

```
CTRL-x:         ClipCut;
CTRL-c:         ClipCopy;
CTRL-v:         ClipPaste;
CTRl-BkSp:      DeleteBlock;
ESC:            HideBlock;

CTRL-a:         M_SelectAll;

CTRL-o:         OpenFile;   
CTRL-n:         OpenFile;           /* better than nothing */
CTRL-d:         ChangeDirectory;    /* not standard */
CTRL-s:         SaveFile;

CTRL-w:         CloseWindow;
CTRL-q:         Quit;

CTRL-f:         GetFindString;
CTRL-g:         RepeatSearch;

CTRL-r:         RunProgram;

CTRL-z:         UnDo;
CTRL-Z:         ReDo;
```
