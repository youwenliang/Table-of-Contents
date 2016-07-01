# Table-of-Contents
Sketch plugin for generating table of contents for documentations

## Artboads Setup
1. Artboard size: 1440 x 1024.
2. Artboard order: top first (Export as PDF order).
3. Having a Cover as the first artboard.

## Titles Setup
1. Use **Symbols** "Header1" & "Header2" as first level titles & second level titles.
2. Use **Overrides** to change the text for "Header1" & "Header2".
3. "Header1" & "Header2" have to be the first(top) layer within an artboard.
4. If a section has multiple artboards, add **"(cont.)"** to the title for additional artboards.

## Example File structure
1. Cover
2. Release Notes
3. Topic A (using Header1)
4. Topic A-1 (using Header2)
5. Topic A-1(cont.) -> continue A-1
6. Topic B (using Header1)
7. Topic B-1 (using Header2)
8. Topic B-2 (using Header2)  
...etc.

![Example Structure](https://raw.githubusercontent.com/youwenliang/Table-of-Contents/master/Sketch%20Artboards.png)

Table of Contents will be generated after the Cover artboard.
You can use "control + option + command + T" as a shortcut to generate Table of Contents.
