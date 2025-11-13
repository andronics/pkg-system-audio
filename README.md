# Audio Control - Volume, playback, and device management

**Package**: `@system/audio`
**Version**: 0.1.0
**Repository**: `pkg-system-audio`

## Overview

Audio Control - Volume, playback, and device management

## Installation

### Prerequisites

This package requires the following external commands:

- `pactl`

### Using pkg-cli

```bash
# Install from GitHub
pkg-cli install @system/audio

# Or install from local source
cd ~/.pkgs
stow audio
```

## Usage

### System Integration

This package provides system integration for audio control - volume, playback, and device management.

```bash
# Control volume
audio volume up
audio volume down
audio volume mute

# Get current volume
audio status
```

## Configuration

Configuration files are typically stored in:
- `~/.config/audio/` - User configuration
- `~/.local/share/audio/` - Application data

## Uninstallation

```bash
# Using pkg-cli
pkg-cli uninstall @system/audio

# Or manual unstow
cd ~/.pkgs
stow -D audio
```

## Development

See [CLAUDE.md](CLAUDE.md) for development guidelines and AI assistance instructions.

## License

MIT License - See [LICENSE](LICENSE) file for details.

## Support

- **Issues**: [GitHub Issues](https://github.com/andronics/pkg-system-audio/issues)
- **Discussions**: [GitHub Discussions](https://github.com/andronics/pkg-system-audio/discussions)
- **Documentation**: [pkgs ecosystem docs](https://github.com/andronics/.pkgs)

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version history.
