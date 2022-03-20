# Changelog

## 2.0.0

### New Features

- Upgrade Excalidraw to `0.11.0`
- Add Support for embedding png and svg images images the current file
- Add Support for directly editing svg files (Use the extension `.excalidraw.svg`)
- Add support for links in drawings

### Breaking Changes

- Deprecate `open in application` command. Please use [Open in External App](https://marketplace.visualstudio.com/items?itemName=YuTengjing.open-in-external-app) instead.
- Deprecate `excalidraw.export.globs`. Since the extension support editing SVGs directly, this is no longer necessary.
- Deprecate all svg export using the command palette. Please use the UI button instead.
- Deprecate theme related options

## 1.3.0

### New features

- Upgrade Excalidraw to 0.9.0
- Add ability to embed scene during export to SVG

## 1.2.0

### New Features

- Upgrade Excalidraw to 0.8.0
- Add autoSave feature (See `excalidraw.save` setting)
- Add support for workspace trust API

### Fixes

- Fix library restore of background tabs
- Disable broken import/export library buttons

## 1.1.0

### New Features

- Upgrade excalidraw to 0.7.0
  - Support tab-to-indent when editing text
- Support to save schema components into a library
- Add a setting to automatically set the output dir on export