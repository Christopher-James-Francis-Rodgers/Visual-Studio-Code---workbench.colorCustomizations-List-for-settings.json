

# workbench.colorCustomizations--2020.08.22u0526.json





## Latest Version Of This File

The latest version of this 'workbench.colorCustomizations'
section for the settings.json file is on GitHub
repository page:

workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode

https:github.com/Christopher-James-Francis-Rodgers/workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode



## Replication Of visualstudio.com Page 'Theme Color' (2020.08.14)

This file is a replication, and re-ordering,
with some details added, of the visualstudio.com page:
'Theme Color':

https:code.visualstudio.com/api/references/theme-color

...as it existed on 2020.08.14, except that the eleven
deprecated (no longer supported) "Notification Colors"
are not included in this file; one misspelled key is
correctly spelled; one key that was renamed has its
new name being used; and two additional keys I discovered
have been added.





## Download The Latest Version Of This File

Download the latest version of this file
'workbench.colorCustomizations--yyyy.MM.dduHHmm.json" at

https:github.com/Christopher-James-Francis-Rodgers/workbench.colorCustomizations-list-for-Visual-Studio-Code-file-settings.json--VS-VSCode

by clicking on that page's upper-right green button
labeled "- Code -", and in the drop-down menu,
click "Download Zip".



### If You Are Not Seeing A Green Button Labeled "- Code -"

If you are not seeing a green button labeled "- Code -",
then your browser window is not wide enough. If after
widening your browser as far as you can, you still do not
see the green button labeled "- Code -", zoom-out to
make everything in your browser smaller by holding down
one of your two [Ctrl/Cmd] keyboard keys, and spin your
mouse wheel downward. Or, zoom-out by [Ctrl/Cmd]+[_/-].
You can zoom back in againg using [Ctrl/Cmd]+[+/=], or
you can reset the zoom level by [Ctrl/Cmd]+[)/0]





### Open The File settings.json In Visual Studio Code

The file settings.json should be located at:

(Windows) C:/Users/[YOUR_USERNAME]/AppData/Roaming/Code/User/settings.json

That file will have been automatically created if you
have made any 'settings' changes to VSCode after
installing VSCode.



### If The File settings.json Does Not Exist, Create One

If the file settings.json does not exist,
create one at the above stated location
by creating a blank text file in the folder 'User'.

Put an opening curly-brace on the first line...
"{" (without the double quotation marks);
leave the second line blank;
put a closing curly-brace on the third line...
"}" (without the double quotation marks);
then save it as "settings.json".



## Other settings.json Files

Please note that VSCode creates an additional
settings.json file for a workspace in the folder
.vscode for that workspace. If you want your color
settings to apply for all of your work in VSCode,
be sure to put them in the settings.json at the
above stated location.

An easy way to open the settings.json file from within
VSCode is the following, but I hesitate to recommend it
because under certain conditions in the past, which I
can not seem to replicate again, under which I must have
had VSCode open to a 'folder' or 'workspace', the
settings.json file which opened was not the global 'User'
settings.json file at
(Windows) C:/Users/[YOUR_USERNAME]/AppData/Roaming/Code/User/settings.json
but rather, was one in a .vscode folder, which explains
why the settings I had made previously seemed to have
disappeared, leading me to abandoning the use of VSCode
altogether. Anyway, to easily open settings.json:





## An Easy Way To Open settings.json In VSCode

Open the file settings.json file in Visual Studio Code
by first opening 'Settings' [Ctrl/Cmd]+[,]
Then click the top-right icon that displays
'Open Settings (JSON)' when you hover your mouse on it.
Note that 'that icon' only appears when the 'Settings'
have been opened first.





## Save Your Existing workbench.colorCustomizations Settings, If Any

It you alredy have any color theme key settings in the
settings.json file, listed under
'workbench.colorCustomizations',
put a copy of those keys in a temporary file for later
insertion back into settings.json.





## Delete The Section 'workbench.colorCustomizations'

Delete the section 'workbench.colorCustomizations' in
settings.json, including the closing curly-brace.





## 'Copy' This File's Contents, 'Paste' Into settings.json File

Open the file
'workbench.colorCustomizations--yyyy.MM.dduHHmm.json'.

'Select all' of this file's contents using the two-key
keyboard shortcut [Ctrl/Cmd]+[A]

Then 'Copy'. [Ctrl/Cmd]+[C]

Go to the bottom of the settings.json file,
and add a new line just above the final closing-brace "}".
Place your flashing cursor on that new line,
and 'Paste'. [Ctrl/Cmd]+[V]

'Save' the settings.json file now that you have modified it.
[Ctrl/Cmd]+[S]





## Your Former workbench.colorCustomizations Settings

If you had any workbench.colorCustomizations "Property
Key": "Value" pairs that you were already using,
copy them out of the temporary file you created earlier,
and put them as a set at the bottom of this file,
about 20-lines up from the bottom, where you see:
[Insert formerly used workbench.colorCustomizations
settings below here...

Then (after you save the settings.json file)
they will take immediate effect, and you can,
at your leisure, transfer the hexidecimal values
from your previous keys into the full listing
that includes the headings, keys, and descriptions,
and follow further below here.





## How To Fix 'Comments Are Not Allowed In JSON Files'

To view this file in Visual Studio Code (VSCode) without
warnings about comments not being allowed in json files,
in the 'Status Bar' at the bottom of the VSCode program
window, and on the right-hand side of the Status Bar,
click on "JSON", and in the pop-up context menu,
click "JSON with Comments".

Now every time you reopen settings.json it will be set as
'JSON with Comments'.

Other JSON files that you open with VSCode, and
subsequently set as 'JSON with Comments', will have to be
reset as 'JSON with Comments' each time you reopen them,
sadly.





## The 471 Keys

The visualstudio.com page 'Theme Colors'
has 480 keys, but 11 of them are deprecated
'Notification' keys which I am ignoring,
and so that leaves 469 keys.



### 469 Keys From visualstudio.com

Of those remaining 469 keys on visualstudion.com,
one was misspelled, and one has been deprecated,
and has been given a new name.



### One Misspelled Key On visualstudio.com

"notebook.cellToolbarSeperator"
is misspelled on visualstudio.com,
and I have renamed it to
"notebook.cellToolbarSeparator"



### One Renamed Key On visualstudio.com

"editorActiveLineNumber.foreground"
on visualstudio.com is deprecated,
and has now been renamed to
"editorLineNumber.activeForeground"



### 2 Additional Keys I Have Discovered By Chance

- editor.onTypeRenameBackground
- notebook.symbolHighlightBackground

My list of 471 keys also includes two additional keys
that I discovered when I cross-referenced the
469 keys from visuslstudio.com against the keys
that are revealed after I set my theme to
'Dark+ (Default Dark)', then opened the
Command Palette [Ctrl/Cmd][Shift]+[P],
and then typed-in/clicked: "Developer: Generate Color
Theme From Current Settings"

I do wonder if additional keys exist which
I have not stumbled across.



## 3 Of 471 Keys Have No Description When Hovered Upon

When a key is un-commented in the file settings.json,
and it is hovered upon by the mouse pointer,
a brief pop-up description is displayed.

Note that if multiple uncommented instances
of the same key exist in the settings.json file,
only the last instance displays the description.

These three keys from the visualstudio.com page,
however, do not display a description when
hovered upon:

- activityBar.dropBackground
- notebook.focusedCellShadow
- panel.dropBackground

I do not know what the implications are of the lack
of a hovered description, and I have not established
whether or not those three keys are valid or not.



## Keys You Put In settings.json Take Precedence

When you put "Property Key": "Value" color settings
into the settings.json file, they override the colors
of your active theme.

They do Not, however, have any control over
the syntax/ semantic colorization of your code.





## Syntax/ Semantic Colors Of Your Code

The 471 keys color settings do not affect the
multi-color variation of the numbers, symbols,
and words of your code.

Those variations are based on the syntax, or semantics
of the numbers, symbols, and words.

Your code's varying text colorization is determined
by Syntax/ Semantic rules set forth by the Theme
you are using. Those Theme rules may themselves then
be overridden by extensions you have installed
that attend to that syntax/semantic colorizing.

If and when I become inclined to address semantic/ syntax
coloring, I will start with re-watching the video:

(YouTube:) "VS Code Change Any Tag Color. Edit Custom
Syntax Colors (No extension)"

https:www.youtube.com/watch?v=Su-cNLe0dgw





## I Recommend The Extension 'Color Vision'

That extension puts a big box with a color sample
in front of each color declaration, even when the
color declaration is commented-out.





## Keys Use A Hexadecimal Format

Hexadecimal color notations supported:
#rgb, #rgba, #rrggbb, #rrggbbaa.
Upper-case is allowed, but I never use it:
#RGB, #RGBA, #RRGGBB and #RRGGBBAA.

Hexadecimal values must be...
(0-9, a-f, A-F)



## Alpha-Value - Opacity

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



## Opacity Alpha-Values Too High, or Omitted
## For Background Colors May Conflict

The alpha-value is optional, in that the color will work
if the alpha-value is omitted, but the alpha-value
should always be used for background colors which target
text characters that will at times also targeted
by additional background color settings.

An example of that is when a search result
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





## Applying a New Color Setting: 'Save' and/or 'Reload'

After you change a color setting, you will need to,
at a minimum, 'Save' the settings.json file to see the
effects of your efforts. Save: [Ctrl/Cmd]+[S]

For some settings, you will have to 'Reload'
Visual Studio Code for the new setting to take effect.





## I Recommend the Extension 'Reload'

While it is true that you can 'reload' VSCode
by shutting down VSCode, and restarting it,
I have found that the easiest way is by installing
the extension "Reload". All that that extension does is
put a button labeled 'Reload' in the bottom right of the
VSCode program window, in the 'status bar', which,
when clicked, reloads VSCode for you.

Then, after VSCode shuts down, it automatically restarts,
and everything is put back as it was before the 'Reload'.

The 'Reload' keyboard shortcut that comes built-in to
VSCode [Ctrl/Cmd]+[R] was not working for me, so I am
happy, happy to have the extension 'Reload'. Nice, nice,
very nice.





## Redundant "Property Key" Declarations

When a Property Key is repeated in the file
settings.json, it will yield a 'warning' to that
effect, but the last occurrence will take affect.

Each valid Property Key in the settings.json file that is
not commented out, when hovered upon, will give you
a brief pop-up description. If a Property Key is repeated,
the pop-up description will only display
when you hover on the last occurrence of it.





## Your Former workbench.colorCustomizations Settings

If you had any workbench.colorCustomizations "Property
Key": "Value" pairs that you were already using, you
can put them as a set at the bottom of this file,
about 20-lines up from the bottom, where you see:
[Insert formerly used workbench.colorCustomizations
settings below here...

Then (after you save the settings.json file)
they will take immediate effect, and you can,
at your leisure, transfer the hexidecimal values
from your previous keys into the full listing above.





## Extension Colors

The following information is quoted from the bottom
of the visualstudio.com 'Theme Colors' page. If it
has any meaning to you, then that is more than it has
for me as yet.

[Quote]
Color ids can also be contributed by extensions through the
'color contribution point'
[https:code.visualstudio.com/api/references/contribution-points#contributes.colors]

These colors also appear when using code complete in the
workbench.colorCustomizations settings and the color
theme definition file. Users can see what colors an
extension defines in the 'extension contributions'
[https:code.visualstudio.com/docs/editor/extension-gallery#_extension-details]
tab.
[End: Quote]


