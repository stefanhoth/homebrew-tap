# homebrew-tap

Make my tools available via [Homebrew](https://brew.sh).

## Setup

Add this tap to Homebrew:

```sh
brew tap stefanhoth/tap
```

## Available Casks

### paperless-ngx-cli

A command-line interface for [Paperless-NGX](https://github.com/stefanhoth/paperless-ngx-cli) — manage your Paperless-NGX document archive from the terminal.

**Install:**

```sh
brew install stefanhoth/tap/paperless-ngx-cli
```

**Supported platforms:**

| OS    | Architecture       |
|-------|--------------------|
| macOS | Intel (amd64)      |
| macOS | Apple Silicon (arm64) |
| Linux | x86\_64 (amd64)   |
| Linux | ARM (arm64)        |

After installation the `paperless` binary is available in your PATH.

## Usage

```sh
# Add the tap (only needed once)
brew tap stefanhoth/tap

# Install a cask
brew install stefanhoth/tap/<cask-name>

# Upgrade to the latest version
brew upgrade stefanhoth/tap/<cask-name>

# Uninstall
brew uninstall stefanhoth/tap/<cask-name>
```
