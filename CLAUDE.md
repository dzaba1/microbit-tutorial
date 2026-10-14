# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project layout

This repo is a MakeCode project (`pxt.json`) that only contains tutorials.

- `lessons/<name>.md` — tutorial, written in Polish.
- `pxt.json` — every tutorial markdown file must be listed in `files`, otherwise MakeCode will not find it.
- Tutorials are opened with `https://makecode.microbit.org/#tutorial:github:dzaba1/microbit-tutorial/lessons/<name>`.

## Commands

MakeCode projects are normally edited in the MakeCode web editor (makecode.microbit.org) or with the `pxt` CLI (`npm i -g pxt`).

- `pxt install` — fetch dependencies (`pxt_modules/`)
- `make build` (`pxt build`) — validate/build the project
- `make test` (`pxt test`) — run tests (`test.ts` is currently empty)

## Language

Tutorials are written in Polish only and are the default (and only) version. Do not add English copies or `_locales` folders unless the user asks; MakeCode's localized-tutorial lookup (`_locales/<lang>/<path from repo root>.md`) was unreliable here because of server-side caching of the repo.

## References for writing tutorials

- https://makecode.com/writing-docs/tutorials
- https://makecode.com/writing-docs/user-tutorials
- https://github.com/microsoft/pxt/tree/master/docs/writing-docs (source of the writing-docs pages)

## Polish block vocabulary

Block and category names in tutorials must match the Polish MakeCode editor exactly. The reference list (English → Polish) is imported below; check it before writing or editing any ``` ``||category: label||`` ``` reference, and extend it when you learn a new label.

@vocabulary.md
