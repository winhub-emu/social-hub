# configs

Community game configs for WinHub, one JSON file per game and device:
`configs/<Game>/<Game>-<Device>-<SoC>-<id>.json`.

- `index.json` is a compact index of every config (used by the browser at the repo root).
- Browse them with `index.html` (GitHub Pages), or open any file and copy the settings.

Each file has `meta` (device, SoC), `settings` (driver, DXVK, VKD3D, FEX, Proton, environment, ...)
and `components` (the exact versions used).

Game configurations shared from the WinHub app are also posted as issues labelled `Configs`.
