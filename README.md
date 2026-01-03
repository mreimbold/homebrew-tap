# Homebrew Tap

Personal Homebrew tap for [mreimbold](https://github.com/mreimbold)'s CLI tools.

## Installation

```bash
brew tap mreimbold/tap
```

## Available Formulas

| Formula | Description |
|---------|-------------|
| `kaufda-cli` | CLI for kaufda.de local offers |
| `withings-cli` | CLI for Withings Health API |
| `terraformat` | Standalone Terraform/OpenTofu formatter that goes beyond terraform fmt and tofu fmt |

## Usage

Install any formula:

```bash
brew install mreimbold/tap/<formula>
```

Or directly without tapping first:

```bash
brew install mreimbold/tap/kaufda-cli
brew install mreimbold/tap/withings-cli
brew install mreimbold/tap/terraformat
```

## Updates

Formulas are automatically updated when new releases are published.

```bash
brew upgrade mreimbold/tap/<formula>
```
