# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project layout

This repo is a MakeCode project (`pxt.json`) that only contains tutorials.

- `lessons/<name>.md` — tutorial in the default language (English).
- `lessons/_locales/<isocode>/<name>.md` — localized copy (same filename); MakeCode picks the best match for the editor language.
- `pxt.json` — every tutorial markdown file (including each locale copy) must be listed in `files`, otherwise MakeCode will not find it.
- Tutorials are opened with `https://makecode.microbit.org/#tutorial:github:dzaba1/microbit-tutorial/lessons/<name>`.

## Commands

MakeCode projects are normally edited in the MakeCode web editor (makecode.microbit.org) or with the `pxt` CLI (`npm i -g pxt`).

- `pxt install` — fetch dependencies (`pxt_modules/`)
- `make build` (`pxt build`) — validate/build the project
- `make test` (`pxt test`) — run tests (`test.ts` is currently empty)

## Localization

Every tutorial must be available at least in Polish and English. When creating or changing a tutorial, always provide both of these language versions and keep them in sync. Other contributors may add further translations.

## References for writing tutorials

- https://makecode.com/writing-docs/tutorials
- https://makecode.com/writing-docs/user-tutorials
- https://github.com/microsoft/pxt/tree/master/docs/writing-docs (source of the writing-docs pages)
