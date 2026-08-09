# KERQON media assets

Brand and product visuals for the public KERQON GitHub presence.

## Brand

| Asset | Use |
| ----- | --- |
| `logo_horizontal_dark.png` | README / dark backgrounds |
| `logo_horizontal_light.png` | Light backgrounds |
| `logo_stacked_dark.png` | Square / social contexts |
| `logo_stacked_transparent.png` | Overlays |

## Product visuals

| Asset | Role |
| ----- | ---- |
| `control-plane-overview.svg` | Control plane + managed nodes + agent channel |
| `node-model.svg` | Deep node model domains |
| `security-model.svg` | Operator → control plane → agent channel → node |
| `architecture-overview.svg` | Earlier compact architecture overview (kept for compatibility) |

All visuals are self-contained SVGs (no external fonts, scripts, or CDN dependencies) and support light/dark via `prefers-color-scheme`.

## Website-future animation notes

These SVGs are structured so they can later be rebuilt as animated React/SVG components on kerqon.de. Candidate motion layers:

- **data pulses** along agent-channel edges (inventory/metrics flow)
- **heartbeat** on node online indicators
- **relationship discovery** drawing topology edges between node domains
- **command response** acknowledgment from node back to control plane
- **topology edges** emphasizing peer/gateway/VPN relationships
- **security state** subtle channel/authorization state changes

Do not animate these in the GitHub README assets themselves.

These files are **public-repo-owned** and preserved across source snapshot publishes.
