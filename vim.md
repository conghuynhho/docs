## MAGIC VIM


### **Vim in VSCode:**  
<kbd>Ctrl</kbd> + <kbd>H</kbd> : In normal mode: Vim Navigate to the **left** panel  
<kbd>Ctrl</kbd> + <kbd>L</kbd> : In normal mode: Vim Navigate to the **right** panel  
<kbd>Ctrl</kbd> + <kbd>J</kbd> : In normal mode: Vim Navigate to the **below** panel  
<kbd>Shift</kbd> + <kbd>V</kbd> + <kbd>J</kbd> : `Must press V and J at the same time`. Move blow line to be not break line anymore   

#### Vim Shortcut  
<kbd>c</kbd> + <kbd>Number of Word</kbd> + <kbd>l</kbd> : Change a number of letter.  
<kbd>u</kbd> : Undo in Vim (Normal mode).  
<kbd>Ctrl</kbd> + <kbd>o</kbd> : Go to history cursor backward. 
<kbd>Ctrl</kbd> + <kbd>i</kbd> : Go to history cursor forward. 


<kbd>Z + Z</kbd> : Exit document with saving  
<kbd>Z + Q</kbd> : Exit document without saving  
<kbd>g</kbd> + <kbd>f</kbd> : Go to file . 
<kbd>Shift</kbd> + <kbd>\`</kbd> : Switch uppercase -> lowercase..
<kbd>Shift</kbd> + <kbd>u</kbd> : Switch selected to uppercase 
<kbd>u</kbd> : Switch selected to lowercase 
<kbd>Shift</kbd> + <kbd>a</kbd> : Go to end of line -> to Insert Mode
<kbd>Shift</kbd> + <kbd>i</kbd> : Go to start of line -> to Insert Mode

<kbd>Ctrl</kbd> + <kbd>]</kbd> : Go to usage or definition of a variable.  
<kbd>Shift</kbd> + <kbd>8 (*)</kbd> : Go to next occurrence of word  
<kbd>Shift</kbd> + <kbd>3 (#)</kbd> : Go to previous occurrence of word  
<kbd>Shift</kbd> + <kbd>9 (*)</kbd> : Go to empty space line upward  
<kbd>Shift</kbd> + <kbd>0 (*)</kbd> : Go to empty space line downward  


<kbd>v</kbd> + <kbd>i</kbd> + <kbd>\<tag\></kbd> : select in side a HTML tag  
<kbd>v</kbd> + <kbd>a</kbd> + <kbd>\<tag\></kbd> : select out side a HTML tag  
**When in selection press <kbd>o</kbd> or <kbd>O</kbd> to jump around selection**  
#### Command with vim
- Search and replace: 
`:%s/<search-text>/<replace-text>`

- In Visual Mode , select some line and type `:sort` to sort.  
- We can split by `:sp` or `:vs`