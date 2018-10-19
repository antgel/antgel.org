---
permalink: /coding-basics/
title: Coding basics
toc: true
---

<!-- ## Intro -->
<!--  -->
<!-- I've been programming computers for over 30 years, using the shell -->
<!-- for most of that time. Here are some insights, which should help anyone -->
<!-- get up to speed. There are  -->

<!-- ## Terminals -->
<!-- ## Shells -->
## Documentation

### man

`man` is an essential command found on [Unix-like
systems](https://en.wikipedia.org/wiki/Unix-like). Short for manual,
`man` offers access to reference documentation (known as the *manpage*) for every command
on the system. For example, `man ls` shows the manpage for the `ls`
command. Yes, `man man` shows the manpage for the `man` command itself.

#### *nix culture

In some ways, manpages are our first encounter with the hard edge of
\*nix culture. It's a culture which may look obtuse at first, but
rewards a willingness to learn to fish. manpages are the ultimate
reference document and reward investment, however tempting it may seem
to search the Internet to find answers.

## Pagers

A pager is a program that displays text in the terminal in a
user-friendly way, offering facilities such as scrolling and search.

### Scrolling

Pagers are designed to work in a static terminal screen (remember
terminals used to be physical screens).  To understand more, read the
[terminal section](#terminals) above. When editing text in the terminal,
don't make the mistake of scrolling with the scrollbar or mouse wheel.

### less

[`less`](http://www.greenwoodsoftware.com/less/index.html) is
probably the most common pager out there, first written in 1985 and
still going strong. As per its [`man` page](https://linux.die.net/man/1/less):
> Commands are based on both `more` and `vi`.

`more` is an even older pager, and `vi` is the precursor to `vim` (see
the section on [editors](#editors)). So learning `less` commands is a
pretty good way to get used to some common terminal programs.

A simple way to try `less` is to type `man ls` at the shell
prompt. As mentioned [above](#man), this opens the manpage for `ls`.
manpages generally open in the `less` pager.

The most useful commands are:

* `space` - page forward
* `q` - quit
* `h` - help, the command that you can use to learn all the others

Note that many commands have several options, a consequence of decades
of development, absorbing many cultures. Also, on modern systems, the
`PgUp` and `PgDown` keys operate as expected, even though a real guru
doesn't want to leave the main keyboard. ;)

## Editors

A good editor is the core of every coder's toolchain. For most of
history, [Vim](https://www.vim.org/) and
[Emacs](https://www.gnu.org/software/emacs/) have been the obvious
choices. As coding has become friendlier, other contenders have entered
the fray. Vim and Emacs are still the big guns, but learning and
customizing them is a long, if rewarding, journey.

### Atom

According to the folks at GitHub who wrote it, [Atom](https://atom.io/) is designed to be:
> hackable to the core, but approachable on the first day

This makes it suitable for beginners, but powerful enough to last the
course. Due to that, its open-source nature, and its strong community, I
recommend Atom for most beginners. I personally use Vim with a [custom
configuration](https://github.com/antgel/dotfiles-vcsh/blob/master/.vimrc),
and would recommend that for the brave.

#### Useful packages

Many people have written packages to extend Atom's functionality. I
recommend installing some from the start, to make the landing as soft as
possible. The following list is derived from [this rather long list of awesome packages](https://github.com/mehcode/awesome-atom).

* [advanced-open-file](https://atom.io/packages/advanced-open-file)
* [autocomplete-modules](https://atom.io/packages/autocomplete-modules)
* [atom-beautify](https://atom.io/packages/atom-beautify)
* [code-peek](https://atom.io/packages/code-peek)
* [editorconfig](https://atom.io/packages/editorconfig)
* [file-icons](https://atom.io/packages/file-icons)
* [linter](https://atom.io/packages/linter)
* [linter-eslint](https://atom.io/packages/linter-eslint)
* [minimap](https://atom.io/packages/minimap)
* [terminal-plus](https://atom.io/packages/terminal-plus)

If you try to install a package that requires dependencies, Atom will
ask you if you want to install the dependencies. Say yes.

Once you've installed a package, you can tweak its settings in the `Package` menu.

<!-- ### Vim -->
<!--  -->
<!-- As I said above, I don't recommend Vim for most beginners. However, it's -->
<!-- a good idea to have a handle on some basic Vim commands. -->

<!-- ## Shell -->
<!--  -->
<!-- ### Basic commands -->
<!--  -->
<!-- ## Git -->
<!--  -->
<!-- ### Basic commands -->
<!--  -->
<!-- * `git status` -->
<!-- * `git fetch` -->
<!-- * `git pull` -->
<!-- * `git rebase` -->
<!-- * `git reset` -->
<!-- * `git clean` -->
<!--  -->
<!-- ### Merge tool -->
<!--  -->
<!-- Meld -->
<!-- Linters -->
<!-- eslint -->
<!-- mdl -->
