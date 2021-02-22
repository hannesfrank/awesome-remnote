![banner](img/remnote-banner.png)

A list of awesome [RemNote](https://remnote.io) plugins, themes, tutorials and other resources.

[Web](https://www.remnote.io/homepage) | [Desktop](https://www.remnote.io/download) (Windows/Linux/Mac) | [Android](https://play.google.com/store/apps/details?id=com.remnote) | iOS (WIP)

<!-- TODO: Explain how the list works and what the goal is. -->
<!-- **What is this list:** Think if it like a mind map of the RemNote Ecosystem.
**Why is this list:** This project aims to collect the best resources, helping the community grow and enabling you to get the most out of RemNote.
 -->
<!-- This project aims to collect and manage community contributions
 such that the devs can focus on RemNote itself. The builtin tutorials
 are great but there are some outdated and missing parts.
 -->
 <!-- Add contributing guidelines -->

- [Awesome Remnote](#awesome-remnote)
  - [Community](#community)
  - [Integrations](#integrations)
  - [Extensions](#extensions)
    - [Plugins](#plugins)
    - [Themes](#themes)
    - [Custom CSS](#custom-css)
    - [Development](#development)
  - [Tutorials](#tutorials)
    - [Courses](#courses)
- [Education Materials](#education-materials)
  - [Learning](#learning)
    - [Spaced Repetition](#spaced-repetition)
  - [Note-taking](#note-taking)
- [Knowledge Bases](#knowledge-bases)

# Awesome Remnote

## Community

<!-- TODO: Icons -->

_Places to interact with community members and developers._

- [Github](https://github.com/remnoteio)
  - [Issue Tracker](https://github.com/remnoteio/remnote-issues) - Report bugs
  - [Frontend API](https://github.com/remnoteio/remnote-api) - Develop plugins
- [Twitter](https://twitter.com/rem_note) - Daily tips and update notifications
- [Youtube](https://www.youtube.com/channel/UCgETcD9IVBbTIL9OjCoaloA) - Tutorials and update demos
- [Discord](https://bit.ly/REMNOTEdiscord) - Discussions and quick help
- [Discourse Forum](https://forum.remnote.io) - Q/A database and Feature Requests
  <!-- - [Reddit](https://www.reddit.com/r/remNote/) - Deprecated: Replaced by Discorse Forum -->

## Integrations

_How to get data from other services into RemNote._

<!-- TODO: Icons? Might be too much here. -->

- **Chrome Extension: [RemNote Clipper](https://chrome.google.com/webstore/detail/remnote-clipper/ohidiiabdhnlgcaidgndbdbjlhngeboj)** - Save websites and take notes.
- Twitter: [RemNoteBot](https://twitter.com/RemNoteBot/) - Send Twitter messages to RemNote.
- Telegram: [RemNote-bot](https://github.com/pavlohrab/RemNote-bot) - Send notes to Daily Documents.
<!-- - Telegram: [rembot](https://github.com/dmrd/rembot) - Forward Telegram chats to RemNote. -->
- IFTTT: [Use IFTTT with RemNote to create notes and greater self knowledge](https://www.youtube.com/watch?v=f7byM4BIq8o) - Youtube video about how to automatically add data using IFTTT hooks, e.g. from watched Youtube videos, Beeminder goal datapoints and played music on Spotify.
- Airr: [How to setup the Airr + RemNote integration](https://www.youtube.com/watch?v=Y92mPSugGBs) - Import highlights from podcast.
- Zotero: [remnote-zotero-import](https://github.com/hannesfrank/remnote-zotero-import) - Paste literature references.

<!--

## Extensions

### Plugins

_Plugins extend the functionality of RemNote, featured plugins (⭐) can be installed directly from [remnote.io/plugins](https://www.remnote.io/plugins)._

<!-- TODO: describe how to install plugins that aren't featured in the app -->

- ⭐ [Image Search](https://remnoteimagesearch.glitch.me/) - Search and insert images powered by Google Image Search.
- ⭐ [RemNote Graph](https://www.nhanvu327.com/rem-plugins) - Graph Visualization for you knowledge base.
  <small>Implementation currently not published on its [Github](https://github.com/nhanvu327/rem-graph).</small>
- ⭐ Word Cloud - Visualize a document as a word cloud.
- ⭐ Word Counter - Count the number of words on the page.
- [RemNote-Pomodoro](https://github.com/sirvan3tr/RemNote-Pomodoro) - Pomodoro timer and activity logger.
- [remnote-schedule](https://github.com/hannesfrank/remnote-schedule) - Visualize your daily schedule. Inspired by [CrushEntropy.com](https://crushentropy.com/).
- [English Dictionary](img/dictionary-plugin.png) - Look up definition of words
  - Note: As RemNote Plugins are just webpages, you can use any webservice which works well in an iframe.

<!-- TODO: Can we get a link (remnote.io/plugins/add?name=myplugin&width=) to install a plugin with default settings. This would be a first and simple to implement step to a plugin store.
Martin said one can ask the devs to add a plugin.
-->

### Custom CSS

_RemNote's appearance can be customized by pasting in and ticking css blocks on the `⮉ Custom CSS` page._

- [:scroll: RemNote Library.](https://hannesfrank.github.io/remnote-library/#/) - A website to discover and share Custom CSS. Installing CSS Snippets is a just copy&paste.

#### Themes

<!-- Broken: **[RemNoteTheme](https://github.com/ethomasv/RemNoteTheme)** - Modern design theme supporting light and dark mode. -->
- [tskn's Theme](https://hannesfrank.github.io/remnote-library/#/scroll/com.github.hannesfrank.remnote-library.tskn-theme) built by [Eva Thomas](https://github.com/ethomasv)
- [Dracula theme](https://github.com/drstrangez0/Remnote-Dracula-theme) by [drstrangez0](https://github.com/drstrangez0)
<!-- TODO: Show featured snippets here: Kanban, Columns, Icons, Themes -->
<!-- - [Highlight Focsed Rem](./css/README.md#highlight-focused-rem) - Highlight the rem you are editing. -->

### Development

_Things a plugin developer might need._

- [Reference](docs/reference.md) in this repo - Undocumented links like an experimental trash to restore deleted rems and the list of Power-Up rems.
- [Extensions, Plugins & Themes documenentation](https://www.remnote.io/documentation/nFTJ495uTxQTva9TL) in RemNote's Tutorial section.
- [remnote-inspect](https://github.com/hannesfrank/remnote-inspect) - Show datastructure of context, focused Rem and Document.
- [RemNote flavored Markdown.](https://forum.remnote.io/t/custom-rem-level-formatting-with-tags/168?u=hannesfrank) - Description of the syntax to insert content by both pasting and API.
  <!-- TODO: Guides, Github pages plugin template,  -->
  <!-- TODO: Add ability to paste content feature request -->
  <!-- TODO: Add css development tips -->

## Tutorials

_How to use RemNote?_

Get started by going through the interactive tutorial and looking at RemNote's excellent builtin documentation or the official Youtube channel. Then move onto community tutorials.

- [Builtin Documentation](https://www.remnote.io/documentation)
- [Official Tutorial Series](https://www.youtube.com/channel/UCgETcD9IVBbTIL9OjCoaloA/videos)
- [Community video tutorials section of the documentation](https://www.remnote.io/documentation/5fc3c2b94aed570045281735)

Selection of Video Tutorials that cover a specific topic more in depth:

- [How To Use RemNote: Practical Note-taking Advice & Flashcard Types](https://www.youtube.com/watch?v=4m4_q4UEZDE) by Red Gregory
- [How To Use RemNote Pt. 2: Templates & Daily Documents](https://www.youtube.com/watch?v=_NCXph5ZSOE) by Red Gregory
- [Academic Paper Reading Workflow](https://www.youtube.com/watch?v=JOr6V-W9cdU) - PDF Integration by Nabhan

### Courses

_Comprehensive curricula covering all features of RemNote._

Paid (💰) or free (🎓).

- <img alt="german flag" src="img/flag-de.png" height="10px"> 💰 [RemNote – Das beste Lerntool verstehen und effektiv nutzen](https://turningpro.de/courses/remnote/preview) by Erich Heyzel

## Education Materials

_How to make the most out of RemNote?_

<!-- TODO: Add references from my RemNote -->

- [RemNote Tour with Founder Martin Schneider](https://www.youtube.com/watch?v=vlm3_57JuMI) - Interview with Martin Schneider by Robert Haisfield about the role of memory in knowledge management aka spaced repetition.

### Learning

_How to get knowledge into your head._

- :mortar_board: [Learning how to Learn by Barbara Oakley and Terrence Sejnowski.](https://www.coursera.org/learn/learning-how-to-learn) A MOOC of empirically proven learning techniques in the simplest possible terms.
  - :closed_book:[A Mind for Numbers: How to Excel at Math and Science (Even If You Flunked Algebra)](https://www.goodreads.com/book/show/18693655-a-mind-for-numbers) accompanying book, can be read without taking the course or alongside it.
- 📕 [Make it Stick: The Science of Successful Learning\_ by Peter C. Brown, Henry L. Roediger III, Mark A. McDaniel](https://www.goodreads.com/book/show/18770267-make-it-stick) Drawing on recent discoveries in cognitive psychology and other disciplines, the authors offer concrete techniques for becoming more productive learners.
- 📄 _Improving Students’ Learning With Effective Learning Techniques: Promising Directions From Cognitive and Educational Psychology_ by John Dunlosky, Katherine A. Rawson, Elizabeth J. Marsh, Mitchell J. Nathan, Daniel T. Willingham - Paper investigating the (in)effectiveness of learning techniques (elaborative interrogation, self-explanation, summarization, highlighting, keyword mnemonic, imagery use for text learning, rereading, practice testing, distributed practice, and interleaved practice).
  - The easy-to-read summary (popular science publication) "_What Works, What Doesn't"_ can be found [here](https://wcer.wisc.edu/docs/resources/cesa2017/Dunlosky_SciAmMind.pdf).
- :books: [Learning Library](https://www.notion.so/Learning-Library-2ecb646b5e1e4d5c8274c73c3fbb2541) by Moritz Wallawitsch (RemNote Co-founder) - A library with links to resources about: Learning-Psychology, Note-Taking, Spaced Repetition, Memory, Visual Learning, Machine Learning, Attention, Creative thinking, Mental Models, Knowledge Representation, Reading, Connected Thought, Edtech, Learning-journey, and more.

#### Spaced Repetition

_How to not forget what you have learned._

Spaced-Repetition and Active Recall are _the_ best techniques to get knowledge into long term memory. They are deeply integrated into RemNote.

- [How to Remember Everything Forever-ish](https://ncase.me/remember/) by Nicky Case - Playful introduction to spaced repetition.
- [Augmenting Long-term Memory](http://augmentingcognition.com/ltm.html) by Michael Nielsen - Serious introduction to spaced repetition.
- [Twenty rules of formulating knowledge](https://www.supermemo.com/en/archives1990-2015/articles/20rules) by Piotr Wozniak - Practical advice on how to formulate flash cards.

### Note-taking

_How to get knowledge out of your head._

- 📕 [_How To Take Smart Notes: One Simple Technique to Boost Writing, Learning and Thinking – for Students, Academics and Nonfiction Book Writers_ by Sönke Ahrens](https://www.goodreads.com/book/show/34507927-how-to-take-smart-notes) - A description of the Zettelkasten method of note taking and its cognitive psychology underpinnings.
  - [Video of a presentation of key ideas in the book.](https://youtu.be/nPOI4f7yCag)
  - [PDF of slides that provide a visual comparison with other note-taking methods](https://strengejacke.files.wordpress.com/2015/10/introduction-into-luhmanns-zettelkasten-thinking.pdf)

## Knowledge Bases

_Examples of other knowledge bases and how to build them._

<!-- TODO: These are awesome lists. Add glasses icons. -->

- [RichardLitt/meta-knowledge](https://github.com/RichardLitt/meta-knowledge) - 💡 A list of knowledge repositories
- [KasperZutterman/Second-Brain](https://github.com/KasperZutterman/Second-Brain) - A curated list of awesome Public Zettelkastens 🗄️ / Second Brains 🧠 / Digital Gardens 🌱.
- [MaggieAppleton/digital-gardeners](https://github.com/MaggieAppleton/digital-gardeners) - Resources, links, projects, and ideas for gardeners tending their digital notes on the public interwebs.
- [brettkromkamp/awesome-knowledge-management](https://github.com/brettkromkamp/awesome-knowledge-management) - A curated list of amazingly awesome articles, people, applications, software libraries and projects related to the knowledge management space.

<!-- These are not for RemNote itself. 
### Frameworks
Starting a knowledge base from scratch can get chaotic. Here are some frameworks to help you structure.
- Zettelkasten/Evergreen Notes: Todo: Find visual guide/template. Maybe just this to get an idea: https://www.youtube.com/watch?v=jI2b1j9sL0I
  - I think to most important part is labeling permanent notes.
  - Fleeting and literature notes can be considered everything else.
  - Fleeting are represented by daily notes.
- Linking Your Thinking (Obsidian): https://www.linkingyourthinking.com/ Youtube: https://www.youtube.com/channel/UC85D7ERwhke7wVqskV_DZUA/playlists
  - There is also a markdown template which you might be able to import to RemNote directly.
- Pillars, Pipelines & Vaults (Notion): https://www.yearzero.io/notion-course Youtube: https://www.youtube.com/watch?v=d93SGaf82OM
- BASB (PARA): https://maggieappleton.com/basb
-->
