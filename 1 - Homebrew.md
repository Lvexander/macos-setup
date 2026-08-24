# 🛠️ macOS Homebrew Setup

## 1. Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zshrc
eval "$(/opt/homebrew/bin/brew shellenv)"
```

---

## 2. Homebrew Formulae (CLI Tools)

```bash
brew install go                 # Go programming language
brew install hugo               # Configurable static site generator
brew install hf                 # Interact with Hugging Face Hub for ML-related resources
brew install make               # Build tool
brew install nvm                # Node Version Manager – manage multiple Node.js versions
brew install uv                 # Rust-based Python virtual environment/package manager
brew install yarn               # JavaScript package manager
brew install python             # Python programming language
brew install ollama             # Run large language models locally
brew install sevenzip           # File archiver
brew install unar               # Extract various archive formats
```

---

## 3. Homebrew Casks (GUI Apps)

```bash
brew install --cask affinity
brew install --cask claude
brew install --cask discord
brew install --cask displaylink
brew install --cask docker-desktop
brew install --cask firefox
brew install --cask font-jetbrains-mono
brew install --cask font-jetbrains-mono-nerd-font
brew install --cask google-chrome
brew install --cask google-drive
brew install --cask ghostty
brew install --cask logi-options+
brew install --cask localsend
brew install --cask moonlight
brew install --cask obsidian
brew install --cask openvpn-connect
brew install --cask proton-pass
brew install --cask pycharm
brew install --cask steam
brew install --cask unity-hub
brew install --cask vlc
brew install --cask visual-studio-code
brew install --cask tailscale
```

**Proton Authenticator:** https://proton.me/authenticator
