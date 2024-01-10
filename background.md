# Background and motivation

### What is Markdown?

- [Markdown](https://en.wikipedia.org/wiki/Markdown) is a lightweight markup language used to format text
- In WYSIWYG editors (e.g. Word), you click buttons to format text and the changes are immediately visible; in markdown you add syntax to the text to indicate how it should be formatted, e.g. `**xxx**` to indicate bold

### Why use Markdown? 

- **Markdown is simple and intuitive** - don't need to learn a lot of tags and commands, just use symbols to create headings, links, etc.
- **Markdown is portable and compatible** - files with markdown-formatted text can be opened and edited with virtually any text editor or application that supports plain text (which isn't the case with e.g. Word, which locks content into a proprietary file format). This means:
	- You can use it for everything (websites, documents, notes, knowledgebases, catalogs, books, technical documentation...)
	- Can share files with others without compatibility issues
- **Markdown is flexible and extensible** - you can customise Markdown to suit your needs.  There are different 'flavours' or extensions of Markdown that add more features or functionality (e.g. CommonMark and GFM)
	- **Markdown is platform-independent** - you can use it on any device running any operating system

([source 1](https://www.markdownguide.org/getting-started/), [source 2](https://www.linkedin.com/pulse/intro-markdown-benefits-drawbacks-sully-vickers))

### The MOGF approach

- In this guide we set out an approach for working with Markdown to publish content on the web that we term MOGF (Markdown + Obsidian + Git(Hub) + Flowershow)
- This combination or "stack" of tools is free and easy to use, and provides a number of advantages
- **[GitHub](https://github.com/)** is a web-based interface that uses [Git](https://git-scm.com/), the open source version control software that lets multiple people make separate changes to web pages at the same time. ([source](https://digital.gov/resources/an-introduction-github/))
- **[Obsidian](https://obsidian.md/)** is a note-taking software that operates on Markdown files 
	- It previews formatted text
	- Supports an extended version of Markdown that includes majority of elements from CommonMark and GFM, while also introducing its own unique features, like [wiki-links](https://help.obsidian.md/Linking+notes+and+files/Internal+links) or [callouts](https://help.obsidian.md/Editing+and+formatting/Callouts).
	-  Using Obsidian gets around some of the limitations of using GitHub UI:
		- Offline editing
		- GitHub UI will only preview GitHub Flavoured Markdown. And while it's a majority of Markdown you would write, it won't be able to render Obsidian-only (or Flowershow-only) syntax elements, like callouts, wiki-links or inline table of contents
		- It also doesn't allow you to make changes (or to add) multiple files at once
- **[Flowershow](https://flowershow.app/)** is an open-source tool for easily converting markdown files into a website
		- Flowershow template is Obsidian-compatible, meaning it supports (or aims to support) all of the Obsidian Markdown features

### What's Next?

- Next, we'll jump into creating a website from scratch using Markdown and Flowershow.

[Next](tutorial-1)
