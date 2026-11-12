# Decisions

Back to [[Ease Overview]].

## One HTML file, no install (2026-11-12)

Office computers are not powerful and installing software may not be possible. The whole app is one `index.html` with no libraries, no server, and no build step. It opens by double-click.

## Append to one .txt file (2026-11-12)

Matches the existing habit of one Notepad file that stacks up calls. The browser writes to the end of the file and never rewrites what is already there. The existing notepad file can be reused.

## Template editable in the app (2026-11-12)

The template is set up inside the app instead of being hard-coded, so fields can change without touching code.

## Chrome or Edge (2026-11-12)

Writing to a file on disk needs the File System Access API, which only Chrome and Edge have. Both are available at the office.

## Hosted on GitHub Pages (2026-11-12)

The code already lives on GitHub and the app is one static file, so Pages hosts it for free with no upkeep. HTTPS keeps file saving working. Notes and the template never leave the computer; only the empty app is public. The template is stored per address, so it is set up once on the hosted version.

## Kept out on purpose

Search, history view, multiple templates, accounts, syncing. Simple first. See [[Ideas]].
