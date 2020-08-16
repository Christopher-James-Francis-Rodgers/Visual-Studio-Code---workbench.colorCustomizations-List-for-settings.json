
workbench.colorCustomizations--2020.08.16u0347.json



# Latest Version

The latest version of this 'workbench.colorCustomizations' 
section for the settings.json file is on GitHub 
repository page:

workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode

https://github.com/Christopher-James-Francis-Rodgers/workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode

Download the latest file
'workbench.colorCustomizations--yyyy.MM.dduHHmm.json"
by clicking on that page's upper-right green button 
labeled "- Code -", and in the drop-down menu, 
click "Download Zip".

Open the file 
'workbench.colorCustomizations--yyyy.MM.dduHHmm.json'.

'Select all' of its contents using the two-key keyboard 
shortcut [Ctrl/Cmd]+[A]

Then 'Copy' [Ctrl/Cmd]+[C]

Open the file settings.json file in Visusl Studio Code 
by first opening 'Settings' [Ctrl/Cmd]+[,]
Then click the top-right icon that displays 
"Open Settings (JSON)" when you hover your mouse on it.
Note that that icon only appears when the 'Settings' 
have been opened first.

Go to the bottom of the settings.json file,
and add a new line just above the final closing-brace "}".
Place your flashing cursor on that new line, 
and 'Paste' [Ctrl/Cmd]+[V]

'Save' the settings.json file now that you have modified it. 
[Ctrl/Cmd]+[S]



# Fix - Comments Are Not Allowed In JSON Files

To view this file in Visual Studio Code (VSCode) without
warnings about comments not being allowed in json files,
in the 'Status Bar' at the bottom of the VSCode program
windown, and on the right-hand side of the Status Bar,
click on "JSON", and in the pop-up context menu, click
"JSON with Comments".

Sadly, I must repeat that procedure everytime I open
this file in VSCode. 



# 'Theme Color' (2020.08.08)

This is a replication, and re-ordering, 
with some details added, of the visualstudio.com page: 
'Theme Color'...

https:// code.visualstudio.com/api/references/theme-color

...as it existed on 2020.08.08, 
except that the no-longer-supported 
"Notification Colors" settings from that page 
are not included in this file.



# 469 "Property Key": "Value" Pairs

These 469 "Property Key": "Value" color settings 
can override all of the Visual Studio Code (VSCode) 
colors of your active theme's color settings 
except for the syntax/ semantic colorization 
of your actual code.



# Your Existing workbench.colorCustomizations Settings...

Any workbench.colorCustomizations "Property Key": "Value"
pairs that you are already using can be place near the 
bottom of this file, about 20-lines up from the bottom,
where you see: "[Insert formerly used workbench.colorCustomizations
settings below here..."



# Syntax/ Semantic Colors Of Your Code

These color settings do not affect syntax, 
nor semantics colorization of your code.

Your code's varying text colorization is determined 
by Syntax/ Semantic rules set forth by the Theme 
you are using, and by any extensions you have installed 
that attends to that colorizing. 

If and when I become inclined to address semantic/ syntax 
coloring, I will start with re-watching the video:

"VS Code Change Any Tag Color. Edit Custom 
Syntax Colors (No extension) - YouTube"

https://www.youtube.com/watch?v=Su-cNLe0dgw



# The workbench.colorCustomizations Color Settings Format 
is Hexadecimal

Hexadecimal color notations supported: 
#rgb, #rgba, #rrggbb, #rrggbbaa.
Upper-case is allowed, but I never use it: 
#RGB, #RGBA, #RRGGBB and #RRGGBBAA.

Hexidecimal values must be...
(0-9, a-f, A-F)



# Alpha-Value - Opacity

The "a" of the color format "#rgba"
(or the "aa" of "#rrggbbaa")
is the 'Alpha-Value', 
which is the level of 'Opacity',
and which means its level of visibility.

If the optional alpha-value is omitted, 
then the alpha-value defaults to "f", or "ff",
which is fully opaque (visibility), and no transparency. 

If an alpha-value is set to "0", or "00", 
the color will be fully transparent, and will not be seen,
which is true for all color declarations, not just 
background colors.

As another example, the 'bf' of "#000000bf" will render 
'black' with 75% opacity (visibility), and 25% transparency. 



# High, or Omitted Alpha-Values for Background Color

The alpha-value is optional, in that the color will work
if the alpha-value is omitted, but the alpha-value 
should always be used for background colors which target 
text characters that will at times also targeted 
by additional background color settings.

An example of that is when a seach result 
('Find/Replace' result) is displaying a distinct 
background color, and then you 'select' a portion 
of that 'Find/Replace' text.

Then the text you have selected is being targeted by the 
background color of both the 'search result' declaration, 
and the 'selection' declaration.

When one, or both of those background color values 
has its opacity (visibility) alpha-value
set too high (too close to 'f' or 'ff'), 
or if the alpha-value is omitted by you, 
(which then sets the opacity to its default of 
'fully-on',) you risk having one of the two background 
colors obscuring the other.



# Trial and Error Next

I have yet to figure out exactly which background 
settings, and what color settings with what alpha-values
will work in conjunction with each other, so I will be
using 'Trial and Error' to see what works.



# Applying a New Color Setting: 'Save' and/or 'Reload'

After you change a color setting, you will need to,
at a mimimum, 'Save' the settings.json file to see the
effects of your efforts. Save: [Ctrl/Cmd]+[S]

For some settings, you will have to 'Reload'
Visual Studio Code for the new setting to take effect. 



# I Recommend the Extension 'Reload'

While it is true that you can 'reload' VSCode 
by shutting down VSCode, and restarting it,
I have found that the easiest way is by installing 
the extension "Reload". All that that extencion does is 
put a button labled 'Reload' in the bottom right of the 
VSCode program window, in the 'status bar', which, 
when clicked, reloads VSCode for you. 

Then, after VSCode shuts down, it automatically restarts, 
and everything is put back as it was before the 'Reload'. 

The 'Reload' keyboard shortcut that comes built-in to 
VSCode [Ctrl/Cmd]+[R] was not working for me, so I am 
happy, happy to have the extension 'Reload'. Nice, nice,
very nice.



# Repeated "Property Key": "Value" Declarations

In case you are curious, a Property Key that is repeated 
in the settings.json file will yield a 'warning' to that
effect, however, the last occurrence will work just fine.

Normally, each Property Key in the settings.json file
that VSCode recognizes (if it is not commented-out), 
when hovered upon, will give you a brief pop-up 
description.

If a Property Key is repeated,
the pop-up description will only display 
when you hover on the last occurrence of it.

###
