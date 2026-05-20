# scoop-ccm

Scoop bucket for [ccm — Claude Context Manager](https://github.com/mynenikoteshwarrao/claude-context-manager).

## Install

```pwsh
scoop bucket add ccm https://github.com/mynenikoteshwarrao/scoop-ccm
scoop install ccm
```

## Update

```pwsh
scoop update ccm
```

## Uninstall

```pwsh
scoop uninstall ccm
```

## How this bucket is maintained

Manifests in `bucket/` are published automatically by the release workflow in
the main [claude-context-manager](https://github.com/mynenikoteshwarrao/claude-context-manager)
repo on every `v*.*.*` tag push. The source of truth for the manifest lives at
`dist/scoop/bucket/ccm.json` in that repo. Do not edit this bucket by hand.
