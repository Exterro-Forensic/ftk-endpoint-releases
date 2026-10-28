# Exterro FTK Armour Endpoint — agent installers

Release files only: no source code lives here.

Each release (`v<version>`) carries the agent installers built for that version:

| Platform | Files |
|---|---|
| Windows x64 | `ftk-endpoint-<version>-x64.msi` |
| macOS 13+ (Apple silicon) | `ftk-endpoint-<version>.dmg` (*FTK Armour Endpoint.app*: drag it to Applications) |
| Linux x86-64 / arm64 | `.deb`, `.rpm`, `.tar.gz` |

Installers contain no credentials. To connect an agent, download an enrollment
profile from your admin portal's **Enrollment** page and follow the install
commands shown there.
