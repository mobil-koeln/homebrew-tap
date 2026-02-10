# mobil.koeln Homebrew Tap

> Homebrew tap for Deutsche Bahn real-time transit information tools

This Homebrew tap provides easy installation of the `moko` CLI tool and other transit information utilities for the Cologne area.

## What is moko?

`moko` is a command-line interface for querying Deutsche Bahn real-time transit information with an interactive Terminal User Interface (TUI). Get live departure times, delays, and connection information right from your terminal.

## Installation

### Tap this repository

```bash
brew tap mobil-koeln/tap
```

### Install moko

```bash
brew install moko
```

### Quick one-liner

```bash
brew install mobil-koeln/tap/moko
```

## Usage

After installation, you can start using moko immediately:

```bash
# Check version
moko --version

# Run the interactive TUI
moko
```

For detailed usage instructions and features, visit the [main moko-cli repository](https://github.com/mobil-koeln/moko-cli).

## Available Formulas

| Formula | Description | Version |
|---------|-------------|---------|
| `moko` | CLI for querying Deutsche Bahn real-time transit information with interactive TUI | 0.1.0 |

## Updating and Maintenance

### Update the tap

```bash
brew update
```

### Upgrade moko

```bash
brew upgrade moko
```

### Uninstall

```bash
brew uninstall moko
brew untap mobil-koeln/tap
```

## Platform Support

The tap supports the following platforms:
- macOS (Intel and Apple Silicon)
- Linux (x86_64 and ARM64)

## Links

- [moko-cli GitHub Repository](https://github.com/mobil-koeln/moko-cli) - Main project and documentation
- [Report Issues](https://github.com/mobil-koeln/moko-cli/issues) - Bug reports and feature requests
- [Homebrew Tap Repository](https://github.com/mobil-koeln/homebrew-tap) - This tap

## License

This Homebrew tap is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

The `moko` tool itself is also licensed under the MIT License.
