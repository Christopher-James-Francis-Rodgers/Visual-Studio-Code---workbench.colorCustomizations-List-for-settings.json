# workbench.colorCustomizations list for Visual Studio Code file settings.json 2020.08.08 (VS VSCode)

This is a full list of the user modifiable 'workbench.colorCustomizations' color settings for your settings.json file.

The are all commented-out, which means that the ones you enable will have a different text color, allowing you to easily see in your settings.json file those color settings you have modified.

The settings are categorized, and listed in the same manner as the source page, though I have added additional sub-headings.

## These color settings do not relate to syntax, or semantics colorization 

Syntax/ Semantic colorization is done by the Theme you are using, and by any extensions you have installed that attend to that.

[Quote - Paraphrased]

Syntax Highlighting:

Syntax highlighting determines the color and style of (your) code in the text editor... It provides a multi-color contrast to (different kinds) of key words... so that your eyes can more immediately locate a particular (kind of) text among a sea of strings, variables, comments, et cetera.

[End: Quote - Paraphrased]

https://medium.com/@danromans/how-to-customize-semantic-token-colorization-with-visual-studio-code-ac3eab96141b

## Source of This List

My file 
'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt'
is a modified replication of the online reference page:

'Theme Colors'

https://code.visualstudio.com/api/references/theme-color

as it existed on 2020.08.08

I added additional Headings, and edited some of the descriptions.

## What is included

All color settings listed on the visualstudio.com page are in my file in the order they were found online (*1), but I added additional headings for ease of finding a desired setting, or set of settings. I also edited some of the descriptions, expanding upon them for clarity as my limited experience allows. Admittedly, I did not review all of the descriptions.

### (*1) Not included are 'Notification colors' for pre-Feb, 2018 VSCode versions

The 'Notification colors' in my file 'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt' do not include those listed online for Visual Studio Code versions older that 1.21 (February 2018). 

If you are targeting VSCode versions before the 1.21 release, those old no-longer supported 'notification colors' are not included in my file, but are listed online under the heading "Notification colors", and underneath the first set of supported 'Notification color' listings, at...

https://code.visualstudio.com/api/references/theme-color#notification-colors

None of the other settings on that page were stated as being unsupported.

## Insert the contents into 'settings.json' 

The contents of the file 'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt' are suitable for insertion into the VSCode file 'settings.json' 

Open the file 'workbench.colorCustomizations--yyyy.MM.dduHHmm.txt'.

'Select all' of its contents. [Ctrl/Cmd]+[A]

'Copy' [Ctrl/Cmd]+[C]

Open the file settings.json file in Visusl Studio Code by first opening 'Settings' [Ctrl/Cmd]+[,]

Then click the top-right icon that displays "Open Settings (JSON)" when you hover your mouse on that icon. Note that that icon only appears when the 'Settings' have first been opened.

Go to the bottom of the settings.json file, and add a new line just above the final closing-brace "}".

Place your flashing cursor on that new line, and 'Paste' [Ctrl/Cmd]+[V]

'Save' the settings.json file now that you have modified it. [Ctrl/Cmd]+[S].

## Defining a Color - Color Format

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

## Activating a New Color Setting

Each separate color setting is ready to use after you define its color (Eg: #rrggbb, or #rrggbbaa), and then un-comment its line by removing the two forward-slash characters at the beginning of that setting's line.

Save the settings.json file after you modify it. [Ctrl/Cmd]+[S].

Some color settings take effect immediately, but some settings require that you first 'Reload' Visual Studio Code [Ctrl/Cmd]+[R] before the new setting takes effect.

# --2020.08.09u2147
