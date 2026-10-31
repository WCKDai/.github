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
| WCKD HQ | `HQ` | WCKDai/.github, WCKDai/wckd, WCKDai/platform, wckdboy/wckd.ai, wckdboy/hermes-agent, wckdboy/hermes-coolify, wckdboy/hermes-webui-botmode, wckdboy/hermes-webui-themes, wckdboy/coolify-matrix-docker, wckdboy/13ft-coolify, wckdboy/n8n_docker-compose, wckdboy/gmk-kiosk, wckdboy/private-kb, wckdboy/wckdbot, wckdboy/wckdboy.github.io |
| Polykrom | `PK` | WCKDai/polykrom, wckdboy/solidcraft (upstream fork) |
| PolyCore | `PC` | WCKDai/polycore, wckdboy/nightfall-freecad (archived reference) |
| TinyRex | `TREX` | WCKDai/tinyrex |
| Galahad | `GAL` | WCKDai/galahadbot, wckdboy/galahadbot, wckdboy/galahad |
| PERCIVAL | `PCV` | wckdboy/percival |
| Invincible | `INV` | wckdboy/invincible |
| Autobot | `AUTO` | wckdboy/autobot |
| Niobium v2 | `NIO` | wckdboy/niobium, wckdboy/niobium-companion |
| Sovware | `SOV` | wckdboy/sovware |
| Omnie | `OMNIE` | wckdboy/omnieconnect, wckdboy/omnie-dev, wckdboy/omnie-dev-editor-engine, wckdboy/omnie-ios, wckdboy/omnie-edit, wckdboy/omnie-edu, wckdboy/omnie-anim |
| Axit | `AXIT` | wckdboy/axit |
| Public Sites | `WWW` | wckdboy/autobot-www |
| WCKD World | `WLD` | (served from wckdboy/autobot-www) |
| Lab | `LAB` | modules: Eidolon (eidolon, eidolon-hundred), Enjin, Mosaic, OpenEndo (openendo, openendo-www, openendo-engine), Coompile (coompile, coomfy), Blueharden, Quantimation, wckd-gpu, Walkietalkie, OPENARCH, Afterimage, Sealed, Search tools (fsearch, drivesearch), ADAMANT eng kit (agent-engineering) |

Repositories not listed yet (to place or archive): WCKDai/trigon, wckdboy/trigon, wckdboy/BEHOLD,
wckdboy/RoundTable, wckdboy/openhuman-web, wckdboy/godview, wckdboy/p1nk, wckdboy/zxz-red,
wckdboy/MiNALTAN-Signatures, wckdboy/nextcloud-mcp, wckdboy/foolfuuka-searxng,
wckdboy/qBittorrent-Search-Plugins.
