# chezmoi

Bootstrap a new Ubuntu user to my environment.

Start a Bash shell session and run this:

```bash
sudo apt-get install --yes curl git
sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply iainelder/chezmoi
```

The "chezmoi" line is taken from [Chezmoi's installation instructions](https://www.chezmoi.io/install/#one-line-package-install).

This repo should be called dotfiles, but that name is [already taken](https://github.com/iainelder/dotfiles).
