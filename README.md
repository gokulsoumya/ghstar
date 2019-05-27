# ghstar

Star GitHub repos from the command line.

```sh
# set the environment variables GH_UNAME and GH_TOKEN
# to your GitHub username and token/password

$ ghstar gokulsoumya/ghstar
Starred gokulsoumya/ghstar
```

(Because the command line is awesome, browsers are a hassle, and I'm lazy.)

## Installation

`ghstar` is written in Python3, available on PyPI and installable via pip:

```
pip3 install ghstar
```

## Usage

You must first set the environment variables `GH_UNAME` and `GH_TOKEN` to
your GitHub username and token/password. It is recommended to use a
[token](https://github.com/settings/tokens/new) with `public_repo` scope
instead of your password though either one works.

```
$ ghstar.py --help
usage: ghstar [-h] repo

Star GitHub repos from the command line.

positional arguments:
  repo        Name of repo to star

optional arguments:
  -h, --help  show this help message and exit

examples:
  ghstar microsoft/vscode
  ghstar jlevy/the-art-of-command-line

```

## Planned Features

- [ ] Unstar repos
- [ ] Search and star interactively
- [ ] View number of stars for a repo

## Contributing

If you have a feature request or if you've found a nasty lil bug, definitely
open an [issue](https://github.com/gokulsoumya/ghstar/issues). And PRs are,
as always, welcome.
