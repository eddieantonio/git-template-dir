git template dir
================

This is a [template directory][template] for new (and existing) git
repositories.

Features
--------

 - default branch is named `main`
 - build ctags after commits, merges, and checkouts ([thanks @tpope][ctags])
 - default exclude patterns (`.gitignore`) for development on macOS

Install
-------

Clone this... somewhere. Some places include `~/.git_template`:

    git clone https://github.com/eddieantonio/git-template-dir.git ~/.git_template

Then configure it as your template directory:

    git config --global init.templatedir '~/.git_template/template'


[template]: https://git-scm.com/docs/git-init/2.2.3#_template_directory
[ctags]: https://tbaggery.com/2011/08/08/effortless-ctags-with-git.html
