# Plain Plain Text (Planning)

Plain Plain Text is an initiative by [Research Data Services](https://library.columbia.edu/services/research-data-services.html) at Columbia University Libraries.

**Mission:** Facilitating and propagating the use of plain text methods and/or standards in the acquisition, analysis, management, licensing, and dissemination of scholarly knowledge.

More concretely, we aim to have answers when people ask the following
questions:

* I want to write a handsome research paper
* I want to create a modular CV that is both online and a pdf
* I want to create a personal home page
* I want to create an online image archive
* I want to create a handsome conference or workshop website
* I want to simplify the formats my data use
* I want to manage my data in way that follows FAIR conventions
* I want to edit and distribute an academic journal
* I want to license my work so that it can be broadly used

## Getting Started

Very little is implemented, but the idea is that a user should be able to download a script/binary (much like with Homebrew) that puts itself in the user’s `$PATH` and allows for commands like:

```zsh
simple new essay
simple new cv
simple typeset
simple publish
```

As such, the installer would check for Pandoc, etc., and install templates into the Pandoc data folder (`~/.local/share/pandoc/` on a Mac). This is the `simple-pandoc-data` repo.

The `new` command would call up GitHub and clone an initial repository, like `ember new` or `gatsby new`.

As such, repos like `simple-essay` have only content in them; templating is pushed to the data files.

## Links that inspire

* [The Plain Person’s Guide to Plain Text Social Science](https://kieranhealy.org/publications/plain-person-text/) (Kieran Healy)
* [Sustainable Authorship in Plain Text using Pandoc and Markdown](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) (Dennis Tenen and Grant Wythoff)
* [A Plain Text Workflow for Academic Writing with Atom](http://u.arizona.edu/~selisker/post/workflow/) (Scott Selisker)
* [Minimal Computing Homepage](https://go-dh.github.io/mincomp/)
* [Nimble Tents Homepage](https://nimbletents.github.io/)
* [Building a Static Website with Jekyll and GitHub Pages](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages) (Amanda Visconti)
* [our work-flow](http://www.smallaxe.net/sxarchipelagos/workflow.html)
* [Introduction to Plain Text Workflows and Sustainable Publishing](http://www.sitzextase.de/blog/2017/02/22/plain-text/) (Till Gralert)
