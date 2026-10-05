# interactor-spatial-oracle

Lean 4 proofs for a predictive bounding-volume hierarchy, and the code generator that emits its C header.

## What it is for

It proves ghost-expansion and surface-area-heuristic bounds for moving entities, then generates `predictive_bvh.h` from the proven formulas for the multiplayer fabric's engine module.

## Build

```sh
lake build
lake exe bvh-codegen
```

## Licence

MIT; see `LICENSE`.
