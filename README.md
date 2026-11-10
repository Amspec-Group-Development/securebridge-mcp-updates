# SecureBridge MCP - update files

Current version: **1.0.3**

This repository is written by the SecureBridge MCP release pipeline. It contains the installers and the
signed update manifest that installed copies of SecureBridge check. It contains no source code and no
configuration. Do not edit it by hand: installed copies only accept a `latest.json` whose signature
(`latest.json.sig`) was made with the release key, so a manual change simply stops updates.

| File | Purpose |
|---|---|
| `SecureBridge-MCP-1.0.3-x64-user.msi` | Installer for a single user (no administrator rights). Auto-update uses this one. |
| `SecureBridge-MCP-1.0.3-x64.msi` | Installer for all users of a PC (needs administrator rights / Intune). |
| `latest.json` / `latest.json.sig` | Update manifest and its signature. |
