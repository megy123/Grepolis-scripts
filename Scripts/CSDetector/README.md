# CSDetector

Tampermonkey userscript for estimating the likely slowest unit in an incoming Grepolis attack.

It is mainly useful for quickly spotting whether an attack may contain a colonization ship and, in some cases, land catapults. The script provides an estimate, not a guaranteed unit composition.

## Status

Beta. The script is already usable, but it still has important limitations and should be treated as a practical helper rather than a perfect detector.

## What It Does

- Analyzes incoming attack timing
- Estimates the slowest unit in the command
- Focuses especially on colonization ship detection
- Can also be useful for selected catapult cases on the same island

## Limitations

- Mythical units are not fully supported
- Speed bonuses and special effects are not fully accounted for
- Results are heuristic and may be inaccurate outside its main use cases

## Installation

Install directly with Tampermonkey:

[![Install with Tampermonkey](https://img.shields.io/badge/Install%20with-Tampermonkey-black?logo=tampermonkey)](https://github.com/megy123/Grepolis-public/raw/main/Scripts/CSDetector/src/myscript.user.js)

Manual installation:

1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Open the raw script file at [Scripts/CSDetector/src/myscript.user.js](https://github.com/megy123/Grepolis-public/blob/main/Scripts/CSDetector/src/myscript.user.js).
3. Create a new Tampermonkey script, paste the contents, and save it.

## Usage

- Open Grepolis as usual after installing the script
- Inspect incoming attacks from the target town view
- Open a command window and review the estimated slowest unit shown by the script

### Example

1. Open incoming attacks through the active commands icon for the town, not the administrator overview.

![Incoming commands](figures/figure1.png)

2. Open the attack window and inspect the predicted slowest unit.

![Attack command](figures/figure2.png)

## Requirements

- Browser with Tampermonkey support
- [Tampermonkey](https://www.tampermonkey.net/)

## Feedback

If you find a bug or have an improvement idea, open an issue in this repository.
