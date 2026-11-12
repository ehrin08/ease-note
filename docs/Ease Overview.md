# Ease Overview

Ease is a small web app for taking notes during phone calls at work. It replaces the old routine of pasting a template into Notepad for every call.

Related notes: [[Features]] · [[Decisions]] · [[Ideas]]

## What it does

1. Shows the call template as a form.
2. You fill the fields during the call.
3. **Wrap Up** adds the call to the bottom of a .txt file and clears the form for the next call.

## How to use it

1. Double-click `index.html` (opens in Chrome or Edge).
2. Click the **☰** menu in the bottom-right corner, next to Clear. All settings live there, so the form gets the whole window. The app is meant to sit in a small window beside other work.
3. In the menu, click **Open notes file** and pick the .txt file that calls should go into, or **New file** to start one. This is done once. The menu also shows which file is in use.
4. In the menu, click **Edit template** to set up the fields to match the real call template.
5. During a call, type in the fields. Tab moves to the next field.
6. Click **Wrap Up** (or press Ctrl+Enter). The call is saved and the form resets.

After the browser is restarted, the first Wrap Up asks to allow access to the file again. Click allow.

## Moving it to the office PC

Copy `index.html` to the office computer (USB, email, or shared drive) and open it. Nothing to install. The template has to be set up once on that computer, because it is stored in the browser.

## Where things live

| Thing | Location |
|---|---|
| The app | `index.html` in the project folder |
| Project notes | this `docs` folder (open as an Obsidian vault) |
| Template and unsaved draft | the browser's storage on that computer |
| Saved calls | the .txt file chosen in the app |
