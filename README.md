# homebrew-tap

Personal Homebrew tap. Currently hosts:

| Formula | Description |
|---|---|
| [`findjar`](Formula/findjar.rb) | search files and the contents of jar/zip archives — [github.com/mbjarland/findjar](https://github.com/mbjarland/findjar) |

## Install

```bash
brew install mbjarland/tap/findjar
```

After install, generate shell completions if your shell isn't already
picking them up from Homebrew's standard paths:

```bash
findjar --completions zsh  > ~/.oh-my-zsh/custom/plugins/findjar/_findjar
findjar --completions bash > /etc/bash_completion.d/findjar
findjar --completions fish > ~/.config/fish/completions/findjar.fish
```

(Homebrew also installs the completion files to
`$(brew --prefix)/share/{zsh,bash,fish}-completion`. Either path
works — pick what fits your setup.)
