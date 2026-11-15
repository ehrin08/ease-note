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

## Call documentation (live since 2026-11-12)

- [x] Call documentation: write a sentence once with blanks, e.g. `Pt called to {Reason for Call}. {Next Step}.` (☰ > Edit documentation). On Wrap Up, Ease fills it in, copies it to the clipboard for pasting during ACW, and adds it to the saved call as a `Documentation:` line.
- [x] ☰ > Copy last documentation, to get the sentence back on the clipboard
- Blank fields leave nothing behind; renaming a field updates the sentence; an empty sentence turns the feature off.

- [x] By default the documentation is whatever is typed in Case Notes (documentation): Wrap Up copies it for pasting. It is joined into one line, and no extra `Documentation:` line is saved since the field is already in the call.
- [x] Starter text: a field can begin with set text on every new call. Case Notes starts with "Pt called to ". Set per field in Edit template. Untouched starter text counts as empty: it is not saved or copied.
- [x] Default fields are the real call template: Humana ID, TPC, Name, Call Details (multi-line), Case Notes (documentation) (multi-line), Case Number (Documentation No.)
- [x] Edit template > Reset to default puts those fields back

## Live captions (added 2026-11-15)

- [x] ☰ > Live captions: pick the call's browser tab and tick "Also share tab audio". What the caller says appears in a small box above the form.
- [x] Speech is recognized on the computer only. Nothing is sent out, and caption text is never saved to the notes file.
- [x] Captions clear on Wrap Up / Clear and keep running for the next call. ☰ > Stop live captions (or Chrome's "Stop sharing") turns them off.
- The first use downloads a speech pack once; choose Live captions again when it says it is ready.

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
- Live captions need a recent Chrome (about version 139 or later) that can recognize speech on the computer. The call tab has to be picked again each time captions are started. English (US) only.
