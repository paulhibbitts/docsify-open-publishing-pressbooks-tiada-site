# Teaching in a Digital Age – Converted to Docsify-This

> The Pressbooks book [Teaching in a Digital Age: Third Edition](https://pressbooks.bccampus.ca/tonybates/), brought into Grav Open Publishing Space by the [Pressbooks Converter](https://pressbooks-converter.hibbittsdesign.org), then converted to plain Markdown pages for [Docsify-This](https://docsify-this.net/#/) by the [Open Publishing Course Space Bridge](https://open-publishing-course-space-bridge.hibbittsdesign.org).

View it as a website: https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-open-publishing-pressbooks-tiada-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&pagination=true&searchbox=true&collapsibleSidebarGroups=true&collapseSidebarGroups=true

These pages are the bridge's output as it is, shown like the guide in Open Publishing Space: the home page is the Guides page, with a card for the book, and the book is in a folder of its own. The book's home page starts with its cover, title, author and licence, then a card for each part, the sidebar lists its chapters and pages, and Previous/Next buttons follow the pages in order.

The original book is by A.W. (Tony) Bates, licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). The Pressbooks Converter's download went straight into the bridge, with no Grav site in between:

- `home.md` – the Guides page
- `teaching-in-a-2026/` – the book: `README.md` (its home page), its cover image, and a folder for each part
  - `section-1/` – Front Matter
  - `section-2/` … `section-15/` – Chapters 1 to 14, each with its overview (`README.md`) and pages
  - `section-16/` – The book in a nutshell
  - `section-17/` … `section-20/` – Appendices 1 to 4
  - `section-21/` – Back Matter: bibliography and index

Images stay on Pressbooks, as they do when the book is brought into Grav.

Each page also keeps its Grav settings in a hidden note at the top, so the bridge can turn these pages into an Open Publishing Space guide.
