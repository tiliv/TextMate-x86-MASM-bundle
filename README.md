# TextMate Bundle for x86 MASM Language Grammar
If using the TextMate 2 prelease, please replace the `TextMate` component of the installation path to `Avian`.

To install with Git:

	mkdir -p ~/Library/Application\ Support/TextMate/Bundles
	cd ~/Library/Application\ Support/TextMate/Bundles
	git clone git://github.com/tiliv/TextMate-x86-MASM.tmbundle.git

Have TextMate reload its bundles, restart the application, or issue the extra command:

	osascript -e 'tell app "TextMate" to reload bundles'

## What's Included
This bundle adds cursory syntax highlighting for the basics of x86 MASM assembly, including folding for `PROC` and `MACRO` definitions.