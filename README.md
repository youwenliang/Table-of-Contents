# Table-of-Contents
This is a Sketch Plugin I created upon a request from our Mozilla UX team. As a memember of the UX team we usually have to create different specs using Sketch, and we have to manually add a "Table of Contents" page to list out the contents. For this plugin you can just press the shortcut and it will automatically generate a Table of Contents page for you. (There are some rules to follow when you create your spec.)

![Create ToC Menu](https://github.com/youwenliang/Table-of-Contents/blob/master/Images/Screen%20Shot%202019-01-28%20at%202.59.21%20PM.png)
![ToC Artboard](https://github.com/youwenliang/Table-of-Contents/blob/master/Images/Screen%20Shot%202019-01-28%20at%202.59.39%20PM.png)

## Artboads Setup
1. Artboard size: larger than 1440 x 1024 preferred.
2. Artboard order: top first (Export as PDF order).
3. Having a Cover as the first artboard & Release Notes or Version History as the second (Support multiple version history pages now).


## Titles Setup
1. Use **Folders** named "Header1" & "Header2" as first level titles & second level titles.

![Titles Setup](https://github.com/youwenliang/Table-of-Contents/blob/master/Images/Screen%20Shot%202019-01-28%20at%203.01.17%20PM.png)

## Example File structure
1. Cover
2. Release Notes
3. Topic A (using Header1)
4. Topic A-1 (using Header2)
5. Topic A-2 (using Header2)
6. Topic A-3 (using Header2)
7. Topic B (using Header1)
8. Topic B-1 (using Header2)
9. Topic B-2 (using Header2)  
10. Topic C (using Header1)  
...  

![File Structure](https://github.com/youwenliang/Table-of-Contents/blob/master/Images/Screen%20Shot%202019-01-28%20at%203.00.03%20PM.png)
  
Checkout the Example Sketch file for more information: https://github.com/youwenliang/Table-of-Contents/blob/master/Example.sketch
Table of Contents will be generated after the Cover artboard.  
Shortcut: <kbd>control</kbd> + <kbd>option</kbd> + <kbd>⌘command</kbd> + <kbd>T</kbd>

## Additional Options:  
You can change the artboard background color, or change the margin and font size according to the amount of your contents.

## Refresh / Delete your ToC: 
If you've already generated a Table of Contents, you can click the button (<kbd>control</kbd> + <kbd>option</kbd> + <kbd>⌘command</kbd> + <kbd>T</kbd>) again to refresh or delete your current Table of Contents.

![Options](https://github.com/youwenliang/Table-of-Contents/blob/master/Images/Screen%20Shot%202019-01-28%20at%203.00.10%20PM.png)
