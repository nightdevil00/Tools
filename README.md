# Tools

Small standalone Linux applications, one subdirectory each.

## What's here

| Tool | What it does |
| --- | --- |
| [DDWriter](DDWriter/) | GTK3 utility for writing ISO images to USB drives with `dd` — device detection, live progress, optional SHA256 verification and auto-eject |

## Using a tool

Each tool installs from its own subdirectory:

```sh
git clone https://github.com/nightdevil00/Tools.git
cd Tools/DDWriter
./install.sh
```

See each tool's own `README.md` for requirements, manual install steps and usage.

## Layout

```
Tools/
  DDWriter/
```

Each subdirectory is self-contained — its source, `README.md`, and install and
uninstall scripts where it needs them.
