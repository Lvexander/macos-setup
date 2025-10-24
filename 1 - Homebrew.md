# 🛠️ MacOS Homebrew Setup

## 1. Install Homebrew

Run the following command in your terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After installation, configure the environment (example for `zsh`):

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

---

## 2. Install Packages with Homebrew

Use the following syntax:

```bash
brew install <formula_name>         # For CLI tools
brew install --cask <cask_name>     # For GUI applications
```

---

### ✅ Homebrew Formulae (CLI Tools)

```bash
brew install hugo               # Configurable static site generator
brew install huggingface-cli    # Interact with HuggingFace Hub for machine learning related (datasets, models, etc)
brew install nvm                # Node Version Manager – manage multiple Node.js versions
brew install uv                 # Rust-based Python Virutal ENV manager
brew install yarn               # JavaScript package manager
```

---

### ✅ Homebrew Casks (GUI Apps)

```bash
brew install --cask 1password
brew install --cask discord
brew install --cask displaylink
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
brew install --cask steam
brew install --cask unity-hub
brew install --cask visual-studio-code
brew install --cask vlc
```