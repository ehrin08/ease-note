# Features

Back to [[Ease Overview]]. Later ideas go in [[Ideas]].

## Built

- [x] Call form generated from the template
- [x] Single-line and multi-line fields
- [x] Wrap Up: append the call to a .txt file, then reset the form
- [x] Date and time added to every call automatically
- [x] Template editor: add, rename, delete, reorder fields
- [x] Draft kept if the page is refreshed or closed mid-call
- [x] Copy button (fallback when file saving is not available)
- [x] Clear button (reset without saving)
- [x] Ctrl+Enter shortcut for Wrap Up
- [x] Remembers the chosen notes file between sessions
- [x] ☰ menu (bottom-right, next to Clear) holds the settings (notes file, template); no title bar
- [x] Compact layout for a small side window: labels beside fields, buttons pinned at the bottom, Notes box fills the leftover height, fields flow into columns when the window is wide

## On the `test` branch (not live yet)

- [x] Call documentation: write a sentence once with blanks, e.g. `Pt called to {Reason for Call}. {Next Step}.` (☰ > Edit documentation). On Wrap Up, Ease fills it in, copies it to the clipboard for pasting during ACW, and adds it to the saved call as a `Documentation:` line.
- [x] ☰ > Copy last documentation, to get the sentence back on the clipboard
- Blank fields leave nothing behind; renaming a field updates the sentence; an empty sentence turns the feature off.

## Format of a saved call

```
========================================
Call: 2026-11-12 2:35 PM
Caller Name: Jane Cruz
Phone: 0917 555 0101
Reason for Call: Billing question
Notes:
Asked about the October invoice. Sent a copy by email.
Next Step: Follow up Friday
```

## Known limits

- Saving straight to a file works in Chrome and Edge only. Other browsers get Copy.
- If the .txt is open in Notepad, reopen it to see newly added calls.
- Template and draft are stored per browser, per computer.
