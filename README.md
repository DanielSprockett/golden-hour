# Golden Hour 🌅

A little personal command center for messy, overlapping projects — built for the specific chaos of running fifteen or twenty things at once and constantly losing track of what's actually free to work on.

It's one HTML file. No sign-up, no backend, no subscription, nothing to install. Open it in a browser and it just works.

## What it actually does

- **Projects full of tasks.** Each project (Research / Grants / Writing / Personal / Creative) holds its own list of tasks, and tasks get their own type too — Coding, Lab, Analysis, Writing, Follow-Up, Create.
- **Dependencies that do something.** Mark a task as depending on another one — even across different projects — and it stays held up until that other task gets done. You don't have to keep that chain in your head.
- **A "Work on now" strip.** Always at the top: everything that's actually unblocked right now, sorted with the most urgent stuff first. No more staring at a giant list wondering where to even start.
- **Due dates**, with overdue and due-soon flagged automatically so nothing quietly slips.
- **Priority ranking** for both projects and tasks. Give something a lower number and it floats to the top.
- **Archive, Someday, and "show completed."** Finished or parked work disappears from your active view without being deleted — still fully searchable when you need it.
- **Stale task nudges.** Tasks that haven't moved in a while get flagged quietly, so things don't just rot silently.
- **Printable status reports.** Hit Report on any project for a clean, print-friendly summary — good for sharing with collaborators without handing over the whole tool.
- **Dark mode.** It's there.
- **Doc links.** Drop a URL in (Google Doc, Notion, wherever) and it shows up as a one-click link right on the project or task.
- **Google Drive sync.** Optional — lets you keep your data in sync across devices. See setup instructions below.

## Using it

Just open `https://danielsprockett.github.io/golden-hour/` in any browser. Add a project, throw some tasks in, start crossing things off.

On your phone, open that URL in Safari or Chrome and tap **"Add to Home Screen"** — it'll land on your home screen as a tappable icon that opens full-screen, no browser bar, like a regular app.

## Syncing across devices

By default your data lives in your browser's local storage, which means it's tied to a specific browser on a specific device. The **Backup & restore** option in Settings lets you copy your data out as plain text and paste it somewhere else — fine for occasional transfers.

For automatic syncing across devices, there's a **Google Drive sync** option in Settings. It saves your data to a single JSON file in your Google Drive and pulls it down on every other device when you open the app. One-time setup required:

1. Go to [console.cloud.google.com](https://console.cloud.google.com) and create a new project
2. Enable the **Google Drive API** under APIs & Services → Library
3. Go to APIs & Services → Credentials → **Create Credentials → OAuth 2.0 Client ID**
4. Choose **Web application**, and add `https://danielsprockett.github.io` as an Authorized JavaScript origin
5. Copy the Client ID you get, open **Settings** in the app, paste it in, and hit **Connect Drive**

The free tier covers this with room to spare — no charges for normal use.

## Credit

Created by Dan Sprockett · 2026
