# Visit Agenda Planner

Plan a client visit in minutes. Build the agenda, invite people through Outlook, and send the client a read-only copy.

**Open the planner:** https://jagjipru.github.io/visit-agenda/

![Visit Agenda Planner](icon-512.png)

## What it does

- Plans each day in 30-minute slots, with **IST and UK time side by side**. The UK column shows GMT or BST from the real date.
- Holds attendees, venues, notes and a **tentative or confirmed** status for every item.
- **Locks** agreed items so they cannot be moved by accident.
- Opens a **prefilled Outlook invite** for any item, with the attendees and time already set.
- Exports to **PDF** (one page per day) and **Excel**.
- Keeps **several visits** in one place, and starts a repeat visit for the same client in one click.
- Creates a **read-only shareable file** for clients, with no settings and no email addresses.
- Brands each visit with your own title, colours, two logos and two company tags.
- **Backs up automatically** to a file you choose (Edge and Chrome).

## Install it as an app

1. Open https://jagjipru.github.io/visit-agenda/ in **Microsoft Edge**.
2. Click the **three dots**, then **Apps**, then **Install this site as an app**.
3. Tick **Pin to taskbar** and **Create desktop shortcut**, then click **Allow**.

It opens in its own window with its own icon. No admin rights and no installer are needed. Chrome also works, using the install icon in the address bar.

## Your data stays with you

- The planner runs entirely in your browser. There is **no server, no account and no tracking**.
- Agendas are saved in your own browser on your own laptop. Nothing is uploaded, and nobody else can see them.
- This repository holds only the blank tool. It contains no client names or data.

## Back up your work

On first open, the planner asks you to choose a backup file. Choose it once, and every change is then saved to it automatically. A OneDrive folder is a good home. You can also download manual backups from **Settings, then Data and backup**.

Clearing your browser data deletes your agendas, so switch auto-backup on.

## Browser support

| Browser | Planner | Auto-backup |
|---|---|---|
| Microsoft Edge | Yes | Yes |
| Google Chrome | Yes | Yes |
| Safari | Yes | Manual backups only |
| Firefox | Yes | Manual backups only |

## What is in this repository

| File | Purpose |
|---|---|
| `index.html` | The whole planner, in one self-contained file |
| `manifest.webmanifest` | Lets Edge and Chrome install it as an app |
| `icon-192.png`, `icon-512.png` | The app icon |

## Updating

To publish a new version, replace `index.html` with the new file and commit it. Users receive the update the next time they open the app. Their saved agendas are not affected.

## Limitations

- Each person's agendas live in their own browser. Use the backup file or the shareable copy to move work between people.
- Outlook invites open in Outlook on the web, prefilled. You review and send them yourself.
- Data in Edge and Chrome is stored separately. Use one browser for your planner.
