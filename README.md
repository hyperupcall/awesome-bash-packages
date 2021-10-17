# Awesome Basalt

All links packages for [Basalt](https://github.com/hyperupcall/basalt), a Bash package manager

This list contains both applications written in Bash (or POSIX shell) that should be globally installable in addition to _Bash libraries_ that should be installed for a particular local Bash project. Basalt manages both of these cases

Keep in mind that everything listed should be considered at least _bleeding edge_. Many could be considered "stable" due to their respective expansive test suite, but I'll be conservative and label them as beta-quality. I'm dogfooding everything listed here

## General use

- [hyperupcall/woof](https://github.com/hyperupcall/woof) - A generalized version manager (replace pyenv,nvm,n,rvm,rbenv,crenv,phpenv, etc. all at once) (NOT YET RELEASED)
- [hyperupcall/bash-args](https://github.com/hyperupcall/bash-args) - A cute little Bash library for blazing fast argument parsing
- [hyperupcall/bash-object](https://github.com/hyperupcall/bash-object) - Manipulate heterogenous data hierarchies in Bash
- [hyperupcall/bash-toml](https://github.com/hyperupcall/bash-toml) - A kickass Toml parser written in pure Bash
- [hyperupcall/bats-common-utils](https://github.com/hyperupcall/bats-common-utils) - Aggregation of Bats utility libraries
- [hyperupcall/bash-semver](https://github.com/hyperupcall/bash-semver) - Semantic version library for Bash
- [hyperupcall/template-bash](https://github.com/hyperupcall/template-bash) - A working template of how a Basalt Bash package should work
- [hyperupcall/bash-error](https://github.com/hyperupcall/bash-error) - Ergonomic error handling in Bash
- [hyperupcall/bash-algo](https://github.com/hyperupcall/bash-algo) - Common algorithms implemented in pure Bash
- [hyperupcall/shtest](https://github.com/hyperupcall/shtest) - POSIX shell test runner

## Personal use

Because the Basalt ecosystem is so small, I decided to include some packages that I use personally. Of course, they should work on any Linux machine, but documentation and testing is not as extensive as the other repositories listed

- [hyperupcall/glue](https://github.com/hyperupcall/glue) - Hypergeneral boilerplate manager and task runner
- [hyperupcall/choose](https://github.com/hyperupcall/choose) - System for choosing default applications, programs, and utilities
- [hyperupcall/dotshellgen](https://github.com/hyperupcall/dotshellgen) - Dotfile categorization and concatenation
- [hyperupcall/dotshellextract](https://github.com/hyperupcall/dotshellextract) - Extract annotated parts of your shell dotfiles into a separate file

## Miscellaneous

### Similar Lists

- [awesome-bash](https://github.com/awesome-lists/awesome-bash)
- [awesome-shell](https://github.com/alebcay/awesome-shell)

### Similar Package Managers

Basalt works with existing "packages", as defined by both Basher and pkg. Browse their lists as well:

- [Basher](https://www.basher.it/package)
- [bpkg](https://bpkg.sh/packages/name)
