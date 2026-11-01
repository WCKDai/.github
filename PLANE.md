# Where work is tracked

Every project in WCKDai and wckdboy is tracked in Plane, workspace `wckd`
(https://app.plane.so/wckd). This file maps each repository to its Plane project. Agents and people
use it the same way:

- Every nontrivial task has a Plane work item in the repository's project. Find one, or create one,
  before starting.
- A branch name or PR title carries the work item's ID, e.g. `PK-123`. A repository that already
  tracks work in GitHub issues (Polykrom, PolyCore) keeps them; the Plane item links the issue.
- When the work lands, move the item to Done with a link to the PR or commit. If it stalls, say why
  on the item.
- A repository that is not listed goes into **Lab** (a module per repository) until it earns a
  project of its own. Add it to this file in the same change.

| Plane project | ID | Repositories |
|---|---|---|
| WCKD HQ | `HQ` | WCKDai/.github, WCKDai/wckd, WCKDai/platform, wckdboy/hermes-agent, wckdboy/hermes-coolify, wckdboy/hermes-webui-themes, wckdboy/coolify-matrix-docker, wckdboy/13ft-coolify, wckdboy/n8n_docker-compose, wckdboy/gmk-kiosk, wckdboy/wckdboy.github.io |
| Polykrom | `PK` | WCKDai/polykrom, wckdboy/solidcraft (upstream fork) |
| PolyCore | `PC` | WCKDai/polycore, wckdboy/nightfall-freecad (archived reference) |
| TinyRex | `TREX` | WCKDai/tinyrex |
| Trigon | `TRG` | WCKDai/trigon |
| Galahad | `GAL` | wckdboy/galahadbot |
| PERCIVAL | `PCV` | wckdboy/percival |
| Invincible | `INV` | WCKDai/invincible |
| Autobot | `AUTO` | WCKDai/autobot |
| Niobium v2 | `NIO` | wckdboy/niobium, wckdboy/niobium-companion |
| Sovware | `SOV` | WCKDai/sovware |
| Omnie | `OMNIE` | WCKDai/omnie-dev, WCKDai/omnie-dev-editor-engine, WCKDai/omnie-ios, WCKDai/omnie-edit, WCKDai/omnie-edu |
| Axit | `AXIT` | WCKDai/axit |
| Public Sites | `WWW` | WCKDai/autobot-www |
| WCKD World | `WLD` | (served from WCKDai/autobot-www) |
| Lab | `LAB` | modules: Eidolon, Enjin, Mosaic, OpenEndo (openendo, openendo-www, openendo-engine), Quantimation, wckd-gpu, Walkietalkie, OPENARCH, Afterimage, Sealed, Search tools (fsearch, drivesearch), ADAMANT eng kit (agent-engineering) |

This repository is public, so private repositories are not listed here: each one is named in its
Plane project's description (or the Lab module's), which only workspace members can see. Add a
private repository there, not here.

Public repositories not placed yet (to place or archive): wckdboy/BEHOLD, wckdboy/RoundTable,
wckdboy/openhuman-web, wckdboy/nextcloud-mcp, wckdboy/foolfuuka-searxng,
wckdboy/qBittorrent-Search-Plugins.
