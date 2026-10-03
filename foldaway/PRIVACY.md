# Foldaway privacy policy

*Last updated: 3 October 2026*

**In short:** Foldaway keeps everything on your own computer. It has no server, no account, no
analytics and no ads, and it never sells or shares anything about you.

## What Foldaway handles, and why

- **Your open tabs' addresses, titles and site icons.** These are shown on the new tab page, and
  when you put tabs away they're saved into your folders so you can open them again.
- **Your Chrome tab groups' names and colours.** Folders are named after them, and tabs go back
  into their group when you undo or reopen them.
- **Your folders, shortcut circles and settings.** These are what you create in Foldaway: saved
  tabs (address, title, site icon and the date you put them away), your shortcuts, and your
  choices in Settings.
- **Your most visited sites, as Chrome lists them.** Read once, the first time Foldaway opens, to
  start your shortcut circles with the sites you use most. Only the circles are kept.
- **The address each open tab is on.** When you close a tab, Foldaway checks, on your computer,
  whether its page is in one of your folders, and if so asks whether to remove it from there
  too. The addresses are kept in temporary storage that Chrome clears when it closes. You can
  turn the question off in Settings ("When I close a saved tab, ask whether to remove it from
  its folder").
- **A background picture, if you choose one.** Foldaway keeps a smaller copy in its storage on
  your computer, to show behind your folders. It's never uploaded, and it isn't part of backups.
- **When you last looked at each tab.** This is used only to decide which tabs have been idle
  long enough to sleep or be put away. It's kept in temporary storage that Chrome clears when it
  closes.
- **When you last saved a backup.** So that Foldaway can remind you (a small dot on the Settings
  gear) when it's been a month.

Private (incognito) tabs are never shown, saved or put away.

## Where it's kept

In Chrome's extension storage, on your device. It isn't uploaded, synced or copied anywhere by
Foldaway, except into your own Chrome bookmarks if you turn that on (see Backups).

## What leaves your computer

Foldaway itself sends nothing anywhere, and its page loads nothing from the web (even its font
is part of the extension). These things do involve the internet, all of them ordinary browsing,
and only when you ask for them:

- **Searching.** When you search from the new tab page, Chrome sends your search to your default
  search engine, exactly as if you had typed it into the address bar.
- **AI Mode.** The search bar's AI Mode button opens Google's AI Mode with whatever you typed,
  like the same button on Chrome's own new tab page.
- **Opening saved tabs and links.** Opening a saved tab, a shortcut, or one of the Gmail, Images
  and Google apps links loads that website, as any link would.

## Backups

**Settings → Backup → Export** saves a file to your computer that only you control. **Import**
reads a file you choose. Neither sends anything anywhere.

**Keep a copy in Chrome bookmarks** is off unless you turn it on, and Chrome asks for your
permission first. While it's on, Foldaway writes your folders' names and their tabs' titles and
addresses into a "Foldaway" folder in your Chrome bookmarks and keeps it up to date. From there,
your bookmarks are Chrome's: it stores them on your computer and, if you use Chrome sync, syncs
them with your Google account, as it does all your bookmarks. Foldaway itself sends nothing
anywhere. Turning it off stops the copying and gives the permission back; the copy stays in your
bookmarks until you delete it. **Import** can read it back (asking for the permission if it
isn't on).

## Deleting your data

You can remove any saved tab or folder at any time. Uninstalling Foldaway deletes everything it
stored, so export a backup first if you want to keep your folders. A copy in your bookmarks stays
until you delete it.

## Permissions, explained

| Permission | Why Foldaway needs it |
|---|---|
| Read your open tabs (`tabs`) | To list your open tabs and save the ones you put away. |
| Tab groups (`tabGroups`) | To name folders after your tab groups and put tabs back into them. |
| Site icons (`favicon`) | To show each site's icon, taken from Chrome's own icon cache. |
| Most visited sites (`topSites`) | To start your shortcut circles with the sites you visit most, the first time Foldaway opens. |
| Storage (`storage`, `unlimitedStorage`) | To keep your folders on your computer, with no size limit. |
| Alarms (`alarms`) | To check once a minute for tabs that have been idle long enough to sleep or be put away. |
| Search (`search`) | To send searches to your default search engine. |
| Right-click menu (`contextMenus`) | To add "Put this tab away" to the menu you get when you right-click a page. |
| New tab page | To show Foldaway when you open a new tab. |
| Bookmarks (`bookmarks`), optional | Asked for only when you turn on "Keep a copy in Chrome bookmarks" or import from it: to write the copy of your folders into your bookmarks and read it back. |

Foldaway's use of this information follows the
[Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/policies),
including its Limited Use requirements.

## Changes

If this policy changes, the new version will be published here with a new date.

## Questions

Open an issue at
[github.com/victorirtwange/victorirtwange.github.io/issues](https://github.com/victorirtwange/victorirtwange.github.io/issues).
