# homebrew-findjar

Homebrew tap for [findjar](https://github.com/mbjarland/findjar) — a tool
for searching files and the contents of jar/zip archives.

## Install

```bash
brew install mbjarland/findjar/findjar
```

After install, generate shell completions:

```bash
findjar --completions zsh  > ~/.oh-my-zsh/custom/plugins/findjar/_findjar    # zsh / oh-my-zsh
findjar --completions bash > /etc/bash_completion.d/findjar                  # bash
findjar --completions fish > ~/.config/fish/completions/findjar.fish         # fish
```

(Homebrew also installs the completion files to its standard paths
under `$(brew --prefix)/share/{zsh,bash,fish}-completion`. Either path
works — pick what fits your setup.)

