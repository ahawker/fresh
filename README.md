# fresh

Bootstrap a fresh OSX install

## Status

Don't use this. I have shit hardcoded. Some things are parametrized. See [vars](vars).

## Usage

```sh
$ bin/fresh
```

## Fresh Laptop

```sh
chsh -s /bin/zsh
xcode-select --install
cd ~
git clone https://github.com/ahawker/fresh src/github.com/ahawker/fresh
cd src/github.com/ahawker/fresh
bin/fresh
```

## TODO

* [ ] iterm2
* [ ] vscode
* [ ] chrome settings
* [ ] "extras" (work environments)
* [ ] divvy config/license
* [ ] keybase/gpg
* [ ] user icon
* [ ] keyboard laptop (remap control)

## Dependencies

* [ahawker/dotfiles](https://github.com/ahawker/dotfiles)

## Prior Art

* [MikeMcQuaid/strap](https://github.com/MikeMcQuaid/strap)
* [herrbischoff/awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line)
* [mathiasbynens/dotfiles](https://github.com/mathiasbynens/dotfiles)
* [kevinSuttle/macOS-Defaults](https://github.com/kevinSuttle/macOS-Defaults)

## License

[Lol wut?](LICENSE)
