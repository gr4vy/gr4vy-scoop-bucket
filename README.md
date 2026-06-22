# gr4vy-scoop-bucket

A [Scoop](https://scoop.sh) bucket for installing the [Gr4vy CLI](https://github.com/gr4vy/gr4vy-cli) on Windows.

## Install

```powershell
scoop bucket add gr4vy https://github.com/gr4vy/gr4vy-scoop-bucket
scoop install gr4vy
```

## Update

```powershell
scoop update gr4vy
```

## About

This bucket contains a single manifest, [`gr4vy.json`](gr4vy.json), pointing at the
Windows release archives published on the [Gr4vy CLI releases page](https://github.com/gr4vy/gr4vy-cli/releases).

The manifest is **published automatically** by
[goreleaser](https://goreleaser.com) on every Gr4vy CLI release — do not edit
`gr4vy.json` by hand, as changes will be overwritten by the next release.

## License

MIT
