# Centered Network

Omarchy's network bar widget with its popup centered on the active display.
It keeps current upstream behavior, including captive-portal handling, and the
local `q` shortcut for closing the panel.

## Install

```sh
omarchy plugin add https://github.com/Kylar514/omanetwork.center.git --enable
```

The plugin declares `omarchy.network` as its source, so enabling it replaces
the built-in network widget while preserving Omarchy's existing IPC routes.

## Remove

```sh
omarchy plugin remove omanetwork.center
```

Removing it restores the built-in network widget.

## Upstream

This plugin is derived from
[`shell/plugins/panels/network`](https://github.com/omacom/omarchy/tree/quattro/shell/plugins/panels/network)
on Omarchy's `quattro` branch. The `upstream` branch mirrors that directory;
automated pull requests merge upstream changes into the customized `master`
branch for review.

## License

MIT. See [LICENSE](LICENSE).
