
# Contributing to tab-stockpile.plugin.zsh

**tab-stockpile** is a collection of extra tab completions for ZSH.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Contributing to tumult](#contributing-to-tumult)
  - [Contribution Guidelines](#contribution-guidelines)
  - [To add a helper script](#to-add-a-helper-script)
  - [To remove a script](#to-remove-a-script)
  - [Scripts are preferred over aliases and functions](#scripts-are-preferred-over-aliases-and-functions)
  - [Update the ReadMe with your contribution](#update-the-readme-with-your-contribution)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Contribution Guidelines

Please only add tab completions that have a license attached. I'd prefer to avoid the gray area of unlicensed code.
## To add a new tab completion

Submit a pull request. Please use `#!/usr/bin/env interpreter` instead of a direct path to the interpreter, this makes it easier for people to use more recent versions since the ones packaged macOS are usually  stale.

## To remove a tab completion

All of the scripts here were either written by me, copied from blog posts or had an Open Source license. That said, if you wrote something included here and want it removed, either open an issue to discuss the removal or submit a pull request.

## Update the ReadMe with your contribution

Please include an entry in the **Included Scripts** section of `README.md` for any scripts in your PRs so authors get their work credited correctly. Add a link to the source in the comments at the beginning of your script so people can find their other work, and please keep the script descriptions in alphabetical order by script name.
