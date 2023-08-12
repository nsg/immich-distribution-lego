# Lego packaged for Immich Distribution

[Lego](https://github.com/go-acme/lego) is an Let's Encrypt client and ACME library written in Go that I use to manage Let's Encrypt certificates from [Immich Distribution](https://github.com/nsg/immich-distribution). This repo is used as a dependency of the Immich Distribution project and is not intended for direct consumption.

## Usage

```yaml
stage-snaps:
    - immich-distribution-lego/latest/stable
```

## Contents
```
.
├── bin
│   └── lego
├── meta
│   └── snap.yaml
└── snap
    ├── manifest.yaml
    └── snapcraft.yaml
```
