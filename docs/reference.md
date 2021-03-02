# RemNote Reference

## Links within RemNote

_Well known and hidden pages of the RemNote web app._

Note: Anything not in the official docs should not be considered stable and might change.

- [remnote.io/about](https://www.remnote.io/about/) - Info page listing many of the below.
- [remnote.io/help](https://www.remnote.io/help/) - Contact and Feedback form.
- [remnote.io/updates](https://www.remnote.io/updates/) - Release page describing new features.
- [remnote.io/documentation](https://www.remnote.io/documentation/) - Builtin written tutorials and documentation.
- [remnote.io/community](https://www.remnote.io/community/) - Publicly shared pages.
- [remnote.io/homepage](https://www.remnote.io/homepage/) - Access the homepage when you are logged in.
- [remnote.io/queue](https://www.remnote.io/queue/) - Spaced repetition queue.
- [remnote.io/knowledge-base](https://www.remnote.io/knowledge-base/) - List of your documents.
- [remnote.io/cards](https://www.remnote.io/cards/) - List of your flash cards.
- [remnote.io/stats](https://www.remnote.io/stats/) - Statistics on number of rems and flashcards.
- [remnote.io/plugins](https://www.remnote.io/plugins/) - Install and configure plugins.
- [remnote.io/trash](https://www.remnote.io/trash/) - Recover deleted notes.
- [remnote.io/settings](https://www.remnote.io/settings/) - Application Settings.
  - [remnote.io/keyboard_shortcuts](https://www.remnote.io/keyboard_shortcuts) - Directly access shortcut settings.
- [remnote.io/api](https://www.remnote.io/api/) - Frontend/backend API reference.
- [remnote.io/api_keys](https://www.remnote.io/api_keys/) - Manage API keys for backend plugins.
- [remnote.io/export](https://www.remnote.io/export) - Export/backup all your Rem to various formats (Plain Text, Markdown, HTML, OPML, JSON, Anki). The Full Raw Backup (JSON) contains all your data and can be used to restore your account.
- [remnote.io/import](https://www.remnote.io/import) - Import Rem from various formats (Roam Research, Workyflowy, Dynalist, RemNote, Anki, Markdown, Copy&Paste Text/Markdown). The RemNote import takes a Full Raw Backup (JSON) and can fully restore your Knowledge Base.

## URL Scheme

Some paths take rem ids as arguments:

- `document/*`
  - `document/REM_ID` opens this rem as a page.
  - `document/REM_ID?locationAnchor=HIGHLIGHT_REM_ID` focuses a child rem on the opened page.
  - `document/LEFT_REM_ID/RIGHT_REM_ID` to open two rems in split view.
- `queue/*`
  - `queue/REM_ID` practice all rem in `document/REM_ID` _with_ spaced repetition, i.e. don't ask flashcards which are not due yet.
  - `queue/REM_ID/all` practice all rem in `document/REM_ID` _without_ spaced repetition, i.e. ask flashcards even if they are not due. **TODO:** Check how the due time changes when you practice something due far in the future multiple times in a row. (You should not get too much credit.)
- `export/REM_ID` export a specific rem. ([remnote.io/export](https://www.remnote.io/export) to export all rem)

## Power-Up Rems

Power-Up rems are a special kind of rem which implement an additional functionality.

- ⮉ Document Sidebar - Configure the sidebar sections.
- ⮉ Custom CSS - Configure appearance.
- ⮉ Daily Document - List of all Daily Notes.
- ⮉ Thought Queue - Special document to store fleeting notes. There is a shortcut to directly add to it. This shortcut is system wide for the desktop app.

- ⮉ Document - Turn a Rem Into a document (visible in document list) or folder.
  - ⮉ Status - Pinned/Draft/Finished
  - ⮉ Source - A Reference. Displayed below the title.
- ⮉ Todo - Todo 
- ⮉ Highlight - Coloring a Rem.
  - ⮉ Color
- ⮉ Header
  - ⮉ Size - H1/H2/H3
- Stub - Not exactly a Power-Up, but a builtin tag which is created when you make a new reference.
- ⮉ Tag - List of all rems used as a tag.

- ⮉ Automatically Sort - Keep children sorted.
- ⮉ Automatically Add Template - Templates tagged with this automatically add all slots when used.

- ⮉ Extra Card Detail - Tag a children of a flash card with this to show it on the back of the card as well.

- ⮉ File - Stores metadata for files uploaded to RemNote (currently only .pdf).
