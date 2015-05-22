# TextFlow

TextFlow is a set of Automator workflows for text manipulation in any OS X text control where built-in OS X text tools might be unavailable or insufficient.

<img src="screenshots/screenshot-textflow-menu.png" alt="Screenshot of TextFlow menu" width="600" height="321">

<img src="screenshots/screenshot-textflow-transforms.png" alt="Screenshot of TextFlow transforms" width="384" height="683">

## Workflows

- Paste and Transform Text
- Transform Selected Text
- Paste as Plain Text

## Text transforms

- Fix Paragraphs
- Extract URL
- Extract Email Address
- Unescape URL
- Plain List
- Remove Duplicate Lines
- Merge All Lines
- Remove Empty Lines
- Remove Extra Spaces
- Dumb Punctuation
- Remove Quotes
- Text Substitution
- Transliterate
- Smart Units
- Smart Punctuation
- Sentence Case
- Upper Case
- Lower Case
- Title Case
- Sort Lines in Ascending Order
- Sort Lines in Descending Order
- Unordered List
- Ordered List
- Copy to Clipboard\*

Note: by default, TextFlow removes any formatting from the text.

\* – Some contenteditable fields in browsers ignore TextFlow output and paste from Clipboard. Include this option to fix the issue.

## Install

1. Download [the latest release](https://github.com/vmdanilov/TextFlow/archive/master.zip).
2. Unpack the archive.
3. Double click workflows to install for a current user. If Gatekeeper does not allow the installation, right-click (or <kbd>⌘ Command</kbd> + Click) on a workflow and choose Open.

## Usage

1. Run TextFlow workflows from Services menu of current application.
2. Select transforms from the next list.
3. Click *OK* or press <kbd>⎋ Esc</kbd> to apply, click *Cancel* or press <kbd>↵ Enter</kbd> to cancel.

You can assign global shortcuts via * > System Preferences > Keyboard > Shortcuts > Services > Text*.

Recommended shortcuts:

- *Paste and Transform Text*: <kbd>⌃ Control</kbd> <kbd>⌥ Option</kbd> <kbd>⌘ Command</kbd> <kbd>V</kbd>
- *Transform Selected Text*: <kbd>⌃ Control</kbd> <kbd>⌥ Option</kbd> <kbd>⌘ Command</kbd> <kbd>T</kbd>
- *Paste as Plain Text*\*: <kbd>⇧ Shift</kbd> <kbd>⌘ Command</kbd> <kbd>V</kbd>

\* – For the sake of consistency, it is also recommended to assign the same global shortcut to *Paste and Match Style* command via * > System Preferences > Keyboard > Shortcuts > App Shortcuts > All Applications*.

<img src="screenshots/screenshot-paste-and-match-style-shortcut.png" alt="Screenshot of assigning Paste and Match Style shortcut for all Apps" width="780" height="693">

## Contributing

Please report bugs, share your ideas or code on Github [TextFlow](https://github.com/vmdanilov/TextFlow) or Twitter [@vmdanilov](https://twitter.com/vmdanilov).

If you like the project, you may [donate some money](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9P6XZDBV7UJKE) via PayPal.

## License

Copyright (c) 2015 Vlad Danilov. Released under [the MIT license](LICENSE.md).