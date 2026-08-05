# SAMPM

SAMPM is a modern, open-source multiplayer platform and SDK for Grand Theft Auto: San Andreas Mobile. It provides a native client, dedicated server, Lua scripting API, asset streaming, and development tools that allow developers to create their own multiplayer experiences without building everything from scratch.

Unlike traditional multiplayer modifications, SAMPM is designed as a framework rather than a single game mode or client. Developers can build their own launchers, servers, resources, and gameplay while SAMPM handles the difficult parts such as networking, GTA integration, synchronization, asset streaming, and scripting.

> Project Status: 🚧 Early Development

---

## Vision

Our goal is to become the open-source foundation for GTA: San Andreas Mobile multiplayer.

Developers should be able to focus on creating their game instead of reverse engineering GTA or implementing networking from scratch.

---

# Features

### Multiplayer Runtime

- Dedicated native server
- Native Android client
- Cross-version GTA support
- Modern networking protocol
- Entity synchronization
- Player synchronization
- Vehicle synchronization
- Object streaming
- RPC/Event system

---

### Lua API

Write gameplay entirely in Lua.

```lua
function OnPlayerJoin(player)
    player:SendMessage("Welcome to the server!")
end
```
No engine modifications required.

---

### Resource System

Everything is a resource.

```
resources/
    freeroam/
    roleplay/
    race/
    admin/
```
Each resource contains its own scripts, assets, configuration and metadata.

---

### Asset Streaming

Server automatically streams:

- Models
- Textures
- Maps
- Sounds
- Resources

No manual installation for players.

---

### Custom Content

Support for:

- Custom maps
- Custom objects
- Vehicle packs
- Model replacements
- New vehicles
- Texture replacements

---

### Client Builder

Generate your own branded client.

Configure:

- Package name
- Application name
- Launcher branding
- Icons
- Splash screen
- Supported GTA versions
- Android SDK versions

Build your own launcher without modifying the engine.

---

### Launcher

Includes:

- Server browser
- Auto updates
- GTA detection
- Asset downloads
- Cache management

---

### Plugin SDK

Extend the server with native plugins.

---

# Project Structure

```
client/
server/
shared/
sdk/
launcher/
builder/
protocol/
resources/
docs/
tools/
examples/
```
---

# Supported Platforms

Client

- Android (planned)
- iOS (future)

Server

- Linux
- Windows
- macOS

---

# Supported GTA Versions

Planned support includes:

- GTA SA Mobile 2.00
- GTA SA Mobile 2.10
- GTA SA Mobile 2.11
- Netflix Edition

---

# Philosophy

SAMPM is designed around several core principles.

- Open source
- Modular
- Cross-version compatibility
- High performance
- Easy scripting
- Easy customization
- Developer-first experience

---

# Roadmap

- Native Android client
- Native dedicated server
- Lua API
- Multiplayer synchronization
- Resource system
- Asset streaming
- Client Builder
- Launcher
- Plugin SDK
- iOS support

---

# Contributing

The project is currently in early development.

Contributions, ideas, documentation, bug reports and discussions are welcome.

---

# License

This software is dual-licensed under the terms of the GNU General Public License v3.0 (GPLv3) and a Commercial Proprietary License.

If you incorporate, link, or build derivative works using this code, your options are:

1. OPEN SOURCE (GPLv3): You may use this software for free under the terms of GPLv3. However, any software you distribute that incorporates, links to, or is derived from this software MUST also be released fully open source under the GPLv3 license.

2. COMMERCIAL / CLOSED-SOURCE LICENSE: If you wish to build, sell, or distribute closed-source, proprietary software without open-sourcing your codebase under GPLv3, YOU MUST PURCHASE A COMMERCIAL LICENSE prior to distribution.

For pricing and purchasing a Commercial Proprietary License, please contact:

[humoyunrustamov99@gmail.com](mailto:humoyunrustamov99@gmail.com)

UNAUTHORIZED CLOSED-SOURCE USE OR DISTRIBUTION OF THIS CODE WITHOUT A VALID COMMERCIAL LICENSE IS A VIOLATION OF INTERNATIONAL COPYRIGHT LAW AND THE GPLv3 LICENSE TERMS.
