# 🐚 macOS ZSH Setup

## My .zshrc configuration

The `.zshrc` file in this repository contains the complete configuration. Copy it to home directory by running:

```bash
cp .zshrc ~/.zshrc
```

---

## Setup context

### Homebrew

After installing Homebrew, ensure it is added to zsh:

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zshrc
eval "$(/opt/homebrew/bin/brew shellenv)"
```

---

### NVM

After installing NVM, create the necessary directory and add the required environment variables for shell profile:

```bash
mkdir ~/.nvm
```

Add the following to `~/.zshrc`:

```bash
export NVM_DIR="$HOME/.nvm"
[ -s "$HOMEBREW_PREFIX/opt/nvm/nvm.sh" ] && \. "$HOMEBREW_PREFIX/opt/nvm/nvm.sh" # This loads nvm
[ -s "$HOMEBREW_PREFIX/opt/nvm/etc/bash_completion.d/nvm" ] && \. "$HOMEBREW_PREFIX/opt/nvm/etc/bash_completion.d/nvm" # This loads nvm bash_completion
```