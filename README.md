# justAssist Hands: firmware releases

Signed firmware update packages (`.mmu`) and `manifest.json` for the justAssist Hands desktop app.
The desktop reads `https://github.com/oizo64/justassist-hands-firmware/releases/latest/download/manifest.json`
and installs a package over USB (`UPDATE`).

Releases are published only by the `Firmware release` workflow of the main project. Do not upload files by hand.
Every package is signed; a board accepts nothing else.