# Eagle Spirit Scoop bucket

[Scoop](https://scoop.sh) manifests for Eagle Spirit tools.

```powershell
scoop bucket add eaglespirit https://github.com/eaglespirittech/scoop-bucket
scoop install perch
```

## Apps

| App | Description |
|-----|-------------|
| [perch](https://github.com/eaglespirittech/perch) | Sit/stand desk control for the IKEA IDÅSEN — exact heights, presets, an hourly stand schedule, and a CLI. |

Installing `perch` gives you the desk app (with a Start menu shortcut) and the `perch-cli`
command on your path. Settings live in `%APPDATA%\Perch`, so they survive updates and
uninstalls.

## Updating

The [Excavator](.github/workflows/excavator.yml) workflow checks upstream releases every
four hours and commits new versions and hashes on its own. To force a check, run that
workflow manually from the Actions tab.
