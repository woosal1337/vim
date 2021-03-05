# Complete `vim` Usage Guide

![](https://res.cloudinary.com/practicaldev/image/fetch/s--paRSwcFn--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://cdn-images-1.medium.com/max/2400/1%2Afv2B1V17KY17nxO2S4-pew.png)

1. Open and Edit a File with `vim` in Terminal:
```
vim filename.file
```

2. Quit / Exit `vim`
```
// ESC at first if you are in edit mode instead of command mode
:q 
``` 

3. Save and Exit `vim`
```
// Write & Quit
:wq
```

4. Change `vim` Modes
```
// Write mode
i

// Command mode
ESC
```

5. Delete current line
```
// Onle 1 and current line deletion

dd
```

6. Delete multiple lines
```
// For 5 lines in a row deletion
5dd

// For as many x lines you want to be deleted
xdd
```

7. Undo Last Changes / Ctrl + Z
```
u
```

8. Redo Changes / Ctrl + Y
```
Ctrl + r
```

9. Searching in `vim`
```
// For a specific 'keyword'

/keyword + ENTER

// For 'custom_parts'
/custom_parts + ENTER
```
```
// Switching among the found keywords

/keyword + ENTER
n #(as many times as you want to go bottom and up)
```

10. Replace the text in the file everywhere
```
// x = text_you_want_to_be_replaced
// y = text_you_want_replace_as

:%s/x/y/g (+c) // For asking everytime to whether change or skip
```
