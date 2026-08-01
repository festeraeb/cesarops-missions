# cesarops-missions

Public **mission** binaries and pipelines that are neither Forge orchestration nor product apps.

## Intended contents

| Monorepo path | Role |
|---|---|
| `satellite/cesarops-satellite/` | STAC / SDB / sat-run |
| `tools/nauti-aeromag/`, `tools/cesarops-aeromagnetic-worker/` | Magnetics |
| `tools/cesarops-detection/` | Detection / validation |
| `pipelines/satellite/`, `pipelines/mag/`, `pipelines/detection_runs/` | Mission JSON (no bulk geodata) |

**Out of scope:** Forge, model weights, `nauticuvs-full`, wreck DB internals ([`wreckhunter2000`](https://github.com/festeraeb/wreckhunter2000)).
