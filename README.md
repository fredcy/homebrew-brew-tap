# Fredcy Brew-tap

## How do I install these formulae?

`brew install fredcy/brew-tap/<formula>`

Or `brew tap fredcy/brew-tap` and then `brew install <formula>`.

## Why?

The **gnupg@2.4.0** package provides gpg functions that work well with Emacs.
Newer versions of gnupg, such as 2.4.3, can cause Emacs to hang.
See https://www.reddit.com/r/emacs/comments/137r7j7/gnupg_241_encryption_issues_with_emacs_orgmode/

You probably want to pin the downgraded package:  `brew pin gnupg@2.4.0`

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

