# Table-of-Contents
Sketch plugin for generating table of contents for Mozilla Spec Documentations.

## Artboads Setup
1. Artboard size: 1440 x 1024 preferred.
2. Artboard order: top first (Export as PDF order).
3. Having a Cover as the first artboard & Release Notes as the second.

## Titles Setup
1. Use **Symbols** "Header1" & "Header2" as first level titles & second level titles.
2. Use **Overrides** to change the text for "Header1" & "Header2".
3. "Header1" & "Header2" have to be the first(top) layer within an artboard.
4. If a section has multiple artboards, add **"(cont.)"** to the title for additional artboards.
5. If you have third level titles or more levels, you don't need to convert them to symbol, it will simply ignore it.

## Example File structure
1. Cover
2. Release Notes
3. Topic A (using Header1)
4. Topic A-1 (using Header2)
5. Topic A-1(cont.) -> continue A-1
6. Topic B (using Header1)
7. Topic B-1 (using Header2)
8. Topic B-2 (using Header2)  
9. Topic C (using Header1)  
  
...  
  
Checkout the Example Sketch file for more information: https://github.com/youwenliang/Table-of-Contents/blob/master/Example.sketch

![Example Structure](https://raw.githubusercontent.com/youwenliang/Table-of-Contents/master/Sketch%20Artboards.png)
![Table Of Contents](https://raw.githubusercontent.com/youwenliang/Table-of-Contents/master/Sketch%20Arboards1.png)

Table of Contents will be generated after the Cover artboard.  
Shortcut: <kbd>control</kbd> + <kbd>option</kbd> + <kbd>⌘command</kbd> + <kbd>T</kbd>

## Additional Options:  
You can change the artboard background color, or change the margin and font size according to the amount of your contents.
You can also check / uncheck to show or hide the page numbers and title prefix numbers.

![Options](https://github.com/youwenliang/Table-of-Contents/blob/master/Sketch%20Options.png)


## Updates: 
If you've already generated a Table of Contents, you can click the button (<kbd>control</kbd> + <kbd>option</kbd> + <kbd>⌘command</kbd> + <kbd>T</kbd>) again to refresh or delete your current Table of Contents.
