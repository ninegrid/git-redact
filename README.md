git-redact
==========

# About

### re·dact
#### /riˈdakt/
verb
> edit (text) for publication.
> * censor or obscure (part of a text) for *legal* or *security* purposes.

Comprehensively deletes and destroys files from a git repository and it's
history.

# Setup

From wherever you stash your clone:

```
$ git clone http://github.com/ninegrid/git-redact.git
$ ln -s ./git-redact ~/bin/git-redact
$ git config --global alias.redact '!sh git-redact'
```

# Usage

```
$ git redact [FILE]...
```

# Todo

Detect git repository in parent directories and convert relative paths from the
current directory to absolute paths from the root of the git repository.

# License

The Unlicense, free and unencumbered released into the public domain.
