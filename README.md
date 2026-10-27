# Exterro FTK Armor Endpoint — agent installers

Release files only: no source code lives here.

Each release (`v<version>`) carries the agent installers built for that version:

| Platform | Files |
|---|---|
| Windows x64 | `ftk-endpoint-<version>-x64.msi` |
| macOS (Apple silicon) | `ftk-endpoint-<version>.pkg` (installs *FTK Armor Endpoint.app*), `ftk-endpoint-<version>-macos.zip` |
| Linux x86-64 / arm64 | `.deb`, `.rpm`, `.tar.gz` |

Installers contain no credentials. To connect an agent, download an enrollment
profile from your admin portal's **Enrollment** page and follow the install
commands shown there.
