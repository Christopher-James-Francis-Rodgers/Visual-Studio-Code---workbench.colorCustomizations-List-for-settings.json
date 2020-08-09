# Visual-Studio-Code--VSCode---workbench.colorCustomizations-List-for-file-settings.json

## What Is Included

The file 
'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt'
is a modified replication of the online reference page for Visual Studio Code [VSCode]:

'Theme Colors'

https://code.visualstudio.com/api/references/theme-color

as it existed on 2020.08.08

I added additional Headings, and edited some of the descriptions that follow each setting.

## Insert the contents into 'settings.json'

The contents of the file 'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt' are suitable for insertion into the VSCode file 'settings.json' (Copy/Paste). 

Paste the contents into the file 'settings.json' in-between the opening curly-brace, and the closing curly-brace.

## What is included

All color settings listed on the visualstudio.com page are in the order they were found on that page (*1), but I added additional headings for ease of finding a desired setting, or set of settings. 

### (*1) Not included are 'Notification colors' for pre-Feb, 2018 VSCode versions

The 'Notification colors' in file 'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt' only apply for Visual Studio Code versions 1.21 (February 2018), and higher. 

If you are targeting VSCode versions before the 1.21 release, those old no-longer supported 'notification colors' are not included in my file, but are listed online under the heading "Notification colors", and underneath the first set of supported 'Notification color' listings, at...

https://code.visualstudio.com/api/references/theme-color#notification-colors

No other settings on that page were defined as unsupported.

## Activating a New Setting

Each separate color setting is ready to use after you define its color (Eg: #rrggbb, or #rrggbbaa), and then un-comment its line by removing the two forward-slash characters at the beginning of that setting's line-- at which point it becomes active.

Some settings take effect immediately, but some settings require that you first 'Reload' Visual Studio Code [Ctrl/Cmd]+[R] before the new setting takes effect.'

## Defining a Color - Format of that Definition

As stated online at 
https://code.visualstudio.com/api/references/theme-color#color-formats

[Quote]

Color values can be defined in the RGB color model with an alpha channel for transparency. As format, the following hexadecimal notations are supported: #RGB, #RGBA, #RRGGBB and #RRGGBBAA. R (red), G (green), B (blue), and A (alpha) are hexadecimal characters (0-9, a-f or A-F). The three-digit notation (#RGB) is a shorter version of the six-digit form (#RRGGBB) and the four-digit RGB notation (#RGBA) is a shorter version of the eight-digit form (#RRGGBBAA). For example #e35f is the same color as #ee3355ff.

[End: Quote]

### Beware 'Opacity'/'Transparency' Conflicts in Editor Panes from overlapping Background (BG) Colors

When two (or more) background color (BG color) CSS decoration declarations apply to the same text character(s), as for example, when 'selecting' text that already has a modified background color because it is a 'Find' (a search result)...

If the opacity is not specified by you for the background colors in-question, it becomes 'ff'; or if your opacity settings for background colors are is too near to 'ff', you risk having one BG setting obscuring the other.

As stated online at 
https://code.visualstudio.com/api/references/theme-color#color-formats

[Quote]

If no alpha value is defined, it defaults to ff (opaque, no transparency). If alpha is set to 00, the color is fully transparent.

Some colors should not be opaque in order to not cover other annotations. Check the color descriptions to see to which colors this applies.

[End: Quote]

# --2020.08.09u2147
