#Vim Cheat Sheet

opening file using vim

```bash
$ vim example.rb
```

for editing in a vim file press ```i```

saving a vim file after using ```i``` press ```esc```
to save and quit use command
```:wq```  when using just ```:q``` will only quit the file.

```e``` 	Move to the end of a word.

```w``` 	Move forward to the beginning of a word.

```3w``` 	Move forward three words.

```W``` 	Move forward a WORD (any non-whitespace characters).

```b``` 	Move backward to the beginning of a word.

```3b``` 	Move backward three words.

```$``` Move to the end of the line.

```0``` Move to the beginning of the line.

```^``` Move to the first non-blank character of the line.

```)``` Jump forward one sentence.

```(``` Jump backward one sentence.

```}``` Jump forward one paragraph.

```{``` Jump backward one paragraph.

```H``` Jump to the top of the screen.

```M``` Jump to the middle of the screen.

```L``` Jump to the bottom of the screen.

```10<PageUp> or 10<CTRL-B>```Move 10 pages up.

```5<PageDown> or 5<CTRL-F>```Move 5 pages down.

```G``` Jump to end of file.

```1G``` Jump to beginning of file (same as gg).

```50G``` Jump to line 50.

```'m``` Jump to the beginning of the line of mark m.

``` `m``` Jump to the cursor position of mark m.

```"``` Return to the line where the cursor was before the latest jump. (Two single quotes.)

``` `` ``` Return to the cursor position before the latest jump (undo the jump). (Two back ticks. This is above the Tab key on some keyboards.)

 ```% ``` Jump to corresponding item, e.g. from an open brace to its matching closing brace.