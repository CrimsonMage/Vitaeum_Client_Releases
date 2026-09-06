# Vitaeum Client Releases

This public distribution repository contains packaged Vitaeum client releases and signed update
metadata only. It does not contain the private application source, build inputs, signing keys, or
symbols.

The client is not a standalone download. Install and start it through the official Vitaeum
Launcher from [Vitaeum_AC](https://github.com/CrimsonMage/Vitaeum_AC); the launcher verifies the
signed release metadata, package size, SHA-256 digest, installed executable hash, and launcher-only
handoff before the client can connect.

Windows and macOS packages intentionally carry no public publisher identity. Platform warnings are
expected; follow the first-launch guidance published with the launcher rather than disabling an OS
security feature globally.
