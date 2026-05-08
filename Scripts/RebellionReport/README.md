# RebellionReport

Grepolis helper for generating standardized rebellion support posts for alliance communication.

## Status

Work in progress. The core idea is implemented, but the project is still tailored to a specific workflow and is not yet packaged as a polished public release.

## What It Does

- Reads the current town state during an active rebellion
- Builds a formatted forum post for support requests
- Includes key defense context such as walls, tower, god, hero, spells, research, and army summary
- Targets alliance forum coordination patterns used on Slovak-speaking worlds

## Repository Layout

- `src/script.js` contains an earlier report-generation implementation
- `src/tm_script.js` contains the Tampermonkey-oriented workflow version

## Current Limitations

- No polished one-click public installer yet
- Assumes Grepolis UI structures and internal models that may change
- Uses workflow-specific wording and output conventions
- Still needs cleanup before being considered stable for general public use

## Intended Use

This project is best treated as an active prototype for alliance support automation, not as a finalized end-user release.
