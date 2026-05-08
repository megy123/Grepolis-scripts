# Grepolis Scripts Collection

[Grepolis](https://grepolis.com/) is a browser-based strategy game by InnoGames. This repository contains personal scripts and development experiments built around alliance coordination, combat awareness, and repetitive in-game workflows.

This project is not affiliated with or endorsed by InnoGames.

## What You'll Find Here

- Reusable Grepolis userscripts
- Early-stage script concepts and prototypes
- Reverse-engineering and request experiments kept separate from public-facing projects

## Project Index

| Project | Status | Summary | Documentation |
|---------|--------|---------|---------------|
| `CSDetector` | Beta | Estimates the likely slowest unit in an incoming attack, mainly for colonization ship and selected catapult detection. | [Open](./Scripts/CSDetector/README.md) |
| `RebellionReport` | Work in progress | Generates standardized rebellion support posts for alliance forum workflows. | [Open](./Scripts/RebellionReport/README.md) |
| `EyeOfArtemis` | Concept | Planned helper for precise attack timing. | [Open](./Scripts/EyeOfArtemis/README.md) |
| `Tormentor` | Concept | Planned helper for sending fake attacks in predefined intervals. | [Open](./Scripts/Tormentor/README.md) |
| `Vanish` | Concept | Planned helper for dodge timing of offensive units. | [Open](./Scripts/Vanish/README.md) |

## Quick Start

1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Open the README of the script you want to use.
3. Install the `.user.js` file if the project already exposes one.
4. Review script-specific limitations before using it on a live world.

## Repository Structure

```text
.
├── Scripts/        Public-facing Grepolis scripts and related assets
├── experiments/    Prototypes, scratch files, and request tests
├── LICENSE
└── README.md
```

Additional directory notes are available in [Scripts/README.md](./Scripts/README.md) and [experiments/README.md](./experiments/README.md).

## Notes

- Several scripts rely on Grepolis client internals and may break after game updates.
- Some tools were built around Slovak alliance workflows and may still contain server- or language-specific assumptions.
- Experimental files are kept outside the main script directories so the repository stays easier to browse.

## Contributing

Issues and improvement suggestions are welcome, especially for broken selectors, changed game behavior, or installation notes that need updating.

## License

This repository is distributed under the terms defined in [LICENSE](./LICENSE).
