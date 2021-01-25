# archman

`archman` is a simple shell script that fetches pages from [Arch Linux's man
page site](https://man.archlinux.org) and displays them to you.

## Installation

It's not yet on the AUR, but will hopefully be one day.

```
$ git clone https://github.com/Insert-Creative-Name-Here/archman.git
$ cd archman
```

And there should be the 'archman' file. If you want to be able to invoke it at
any time, move it to a directory that is on $PATH

## Usage

Simply, just run:

```
$ archman <man_page(s)>
```

and it will fetch you the manual page or give an error if it can't find it.

Additionally, you can specify a section to look in by appending a ".[section]"
to a man page.

For example:

```
$ archman init.1
```

will fetch you the manual page for systemd in section 1
