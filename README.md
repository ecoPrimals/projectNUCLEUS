# projectNUCLEUS

Gate deployment, security validation, and cross-bonding test ground for the
NUCLEUS atomic composition on real hardware.

**Organization**: gardens (products built on ecoPrimals)
**Generation**: gen4 — composition and deployment
**License**: AGPL-3.0-or-later (code), ORC (system mechanics), CC-BY-SA 4.0 (docs)

## What This Is

projectNUCLEUS is the **deployment and validation product** for the ecoPrimals
NUCLEUS composition. It takes primal binaries from plasmidBin, composition
graphs from primalSpring, and standards from wateringHole, and deploys them
onto gate hardware — then validates that the deployed composition is secure,
correct, and sovereign.

```
primalSpring (composition patterns, scenarios)
       ↓ deploy graphs + validation contracts
plasmidBin (binary depot)
       ↓ genomeBins
projectNUCLEUS (deploys + validates on gate hardware)
       ↓ validated gates
cellMembrane (fleet ops, cascade, membrane)
```

**Wave 200+ (2026-11-04)**: SOVEREIGNTY COMPLETE. Tunnel sovereignty achieved —
dromedary (Pure Rust reverse proxy) replaces Cloudflare + Caddy entirely. Tor hidden
service on eastGate. golgi VPS DOWN. WireGuard DISABLED. LAN is just LAN.
17 primals compiled and running. 7 live subdomains. 1,200+ pages served sovereign.
21 sweetGrass braids. Nostr + neutrino + RSS + ActivityPub messaging. Zero cloud.

projectNUCLEUS focuses on three concerns:

1. **Gate deployment** — `nucleus-deploy` CLI (deploy, provision, verify, DNS)
2. **Security validation** — `darkforest` adversarial auditor, membrane pen tests
3. **Sovereign infrastructure** — dromedary, Tor, direct DNS (Porkbun), Nostr identity

## NUCLEUS Atomics

NUCLEUS composes from three atomics, each named for a subatomic particle:

| Atomic | Particle | Primals | Role |
|--------|----------|---------|------|
| **Tower** | Electron | bearDog + songBird + skunkBat + dromedary | Trust boundary — crypto, identity, networking, defense, sovereign TLS |
| **Node** | Proton | Tower + toadStool + barraCuda + coralReef | Compute — workload dispatch, GPU math, shader compilation |
| **Nest** | Neutron | Tower + nestGate + rhizoCrypt + loamSpine + sweetGrass | Storage — content-addressed data, provenance, attribution, messaging |
| **Ferment** | Gluon | sourDough + swarmVine + bingoCube | Coordination — fermentation, gossip, scheduling |

Full NUCLEUS = Tower + Node + Nest + Ferment + Squirrel (AI) + biomeOS (orchestration) + petalTongue (viz).

**17 primals total.** All compiled. All running. All Pure Rust. All `#![forbid(unsafe_code)]`.

| Composition | Particle | Primals | Role |
|-------------|----------|---------|------|
| **Agent** | Photon | Tower + biomeOS + Squirrel | Autonomous agent — AI planning via `signal_plan`, graph execution via `signal.dispatch` |
| **Membrane** | Neutrino | Full NUCLEUS + 23 mushrooms + 35 crons | The living organism — Gaia. Self-maintaining, self-publishing, sovereign. |

The Agent composition is the smallest unit that can reason + act + audit autonomously.
Squirrel decomposes intent into atomic signals, biomeOS dispatches them through tower
primals. `signal_executor.sh` bridges the two via JSON-RPC.

**fieldMouse** is NOT a primal — it is a deployment class (biomeOS chimeras for edge/IoT).
Do not include fieldMouse in primal rosters.

Every gate runs the atomics that match its hardware. A NUC runs Tower. A
workstation runs Node. A storage server runs Nest. biomeOS coordinates
the mesh.

## Bonding Model

Gates connect to each other through chemical bonding patterns:

| Bond | Trust | Use Case |
|------|-------|----------|
| **Covalent** | Shared family seed, full trust | Basement LAN cluster — your machines |
| **Ionic** | Metered, scoped access | Friend's GPU, ABG compute sharing |
| **Metallic** | Delocalized capabilities | Institutional HPC (ICER), datacenter fleet |
| **Weak** | Pre-trust, external APIs | Dark Forest beacons, initial contact |

## Current State

**Wave 200+ (2026-11-04)** — **SOVEREIGNTY COMPLETE.** All external dependencies eliminated. dromedary serves 7 subdomains direct (no Cloudflare, no Caddy, no VPS). Tor hidden service on eastGate. 17/17 primals compiled and running. 21 sweetGrass braids. Nostr broadcasting. RSS self-publishing. REEDit unified surface. The organism speaks for itself.

### Infrastructure

- All **17/17 primals** compiled and deployed — 14 via NUCLEUS systemd, dromedary + biomeOS separate services
- Full provenance chain: BLAKE3 → rhizoCrypt DAG → loamSpine ledger → sweetGrass braid (21 braids)
- **Physical topology (Two Houses)**:
  - INTERNET → ATT modem (.254) → GL-MT6000 Router (.1) → MikroTik (.2) → gates
  - Subnet: 192.168.4.0/24, DHCP .100-.249
  - House 2: TP-Link JetStream (.111) — 10G fiber backbone to House 1
  - WireGuard: **DISABLED** — LAN is just LAN. No mesh overlay.
- **7 live subdomains**: primals.eco (HUD, 167 pages), sporeprint (382), detroit (600+), hypothesis (52), tuebor (35), hud, signal
- **Tor hidden service**: LIVE on eastGate (replaces sporeGate federation role)
- **Port forwards**: HTTP/HTTPS/SMTP/DNS → eastGate (.194)
- **DNS**: Porkbun direct — MX, SPF, DMARC configured for primals.eco
- **AI**: 15 ollama models + 3 custom (gaia, gaia-code, gaia-fast) on RTX 4070
- **Autonomous layer COMPLETE**: 23 mushrooms, 35 crons — self-maintaining, self-publishing
- **golgi VPS**: DOWN — cellMembrane Nest Atomic is **DEPRECATED**. eastGate runs everything.
- **Cloudflare**: FULLY DEPRECATED — dromedary serves TLS direct with ACME
- **Messaging**: Nostr (gaia@primals.eco + ecoPrimal@primals.eco), RSS (1560 items), neutrino (squirrel), ActivityPub (webfinger), WebSub
### Wave 38–157 History (fossil record)

<details>
<summary>Click to expand pre-sovereignty evolution history</summary>

- BTSP dual-auth shadow ACTIVE: BTSPAuthenticator plugin live on JupyterHub
- Provenance pipeline validated: Full 9-phase pipeline through trio. Merkle root + ed25519 witness braid operational
- darkforest --scope outer: 26/26 PASS — clean sweep against live primals.eco
- Dark Forest Glacial Gate PASS: 33 structural checks across 5 pillars
- Deep debt evolution COMPLETE: deploy.sh modularized, darkforest pentest/crypto split
- lithoSpore 7/7 modules PASS Tier 2 (75/75 checks, 117 tests)
- Wave 64 Rust evolution: 265 Rust tests PASS (darkforest 149, tunnelKeeper 48+1, nucleus-deploy 49, nucleus-primals 19)
- Wave 56 deployment standard: `--uds-only` suppresses TCP ports (VPS standard)
- Wave 38 sovereignty shadow FULL PASS: 5-track parity proof + DNS

</details>

### Services (all persistent via systemd)

| Service | URL/Port | Layer | Status |
|---------|----------|-------|--------|
| dromedary | `:80/:443` | Outer membrane | **Sovereign TLS** — ACME, HTTP/2, 7 subdomains, Meta blackwall |
| Tor | `.onion` | Outer membrane | Hidden service — eastGate is the provider |
| gaia-web | `:8080` | Membrane | Data server — HUD + membrane + API |
| Forgejo | `:3000/:2222` | Intracellular | Primary git host — 40+ repos, 3 orgs |
| ollama | `:11434` | Intracellular | AI inference — 15 models + 3 custom |
| 14 NUCLEUS primals | `:9100–9900` | Intracellular | All healthy, user services via `membrane-nucleus@` |
| dromedary | user service | Outer membrane | Separate systemd unit, enabled |
| biomeOS | orchestrator | Intracellular | Composition coordination |

### Deprecated Services (fossil record)

| Service | Was | Status |
|---------|-----|--------|
| ~~cellMembrane VPS~~ | golgi 157.230.3.183 | **DOWN** — VPS unreachable |
| ~~Cloudflare proxy~~ | CDN + TLS | **DEPRECATED** — dromedary serves direct |
| ~~pappusCast~~ | Observer propagation | **DEPRECATED** — sporePrint + biomeOS |
| ~~K-Derm diderm~~ | CF outer → Caddy inner | **DEPRECATED** — no proxy chain needed |
| ~~Caddy~~ | TLS on VPS | **DEPRECATED** — dromedary |
| ~~Stalwart~~ | Mail server | **EJECTED** — Nest Atomic messaging |
| ~~WireGuard~~ | Mesh overlay | **DISABLED** — LAN is just LAN |

### Access Model

Three paths to reach the organism. All serve the same content. No login required for public surfaces.

| Path | URL | Transport | Who |
|------|-----|-----------|-----|
| **WAN** | `https://primals.eco` | dromedary TLS (ACME) | Anyone on the internet |
| **LAN** | `http://192.168.4.194:8080` | gaia-web HTTP | Any device on subnet |
| **Tor** | `http://iqwvbmlg...riid.onion` | Tor hidden service | Anonymous visitors |

### Gate Topology (Two Houses, One Organism)

| Gate | IP | State | Role | Hardware |
|------|-----|-------|------|----------|
| **eastGate** | .194/.103 | **OPEN** | brain+gut — full NUCLEUS, 17 primals | i9-14900K, 96GB DDR5, RTX 4070, 2TB NVMe |
| **graftGate** | .107 | **OPEN** | Mac Mini | Apple Silicon |
| **southGate** | .148 | **OPEN** | compute | — |
| **ironGate** | .237 | **OPEN** | compute | — |
| **blueGate** | .210 | **RISEN** | Windows SSH | — |
| **northGate** | — | **SEARCHING** | House 1/MikroTik side | Polaris |
| **sporeGate** | — | **DORMANT** | traveling node (was CI+mesh) | — |
| ~~golgi~~ | 157.230.3.183 | **DOWN** | was Nest Atomic VPS | DigitalOcean 2GB — destroy |
| ~~golgiLayerLinode~~ | 172.232.85.202 | **DEPRECATED** | was backup | Linode — destroy |

### Security

- **All primal ports bound `127.0.0.1`** — 17 primals, no external exposure except dromedary
- **MethodGate ENFORCED**: 17/17 primals ship MethodGate. Unauthenticated calls → `-32001 PERMISSION_DENIED`
- **Ionic tokens LIVE**: BearDog Ed25519-signed scoped tokens with expiry and JTI
- **dromedary Blackwall**: Meta/Facebook IP ranges blocked at the proxy level
- **Identity architecture**: Kevin Mok/Tamison NEVER published from public surfaces. ecoPrimal is the handle. INVIOLABLE
- **darkforest v3.0**: modular Rust security validator — 14 source modules, 149 tests, zero C deps
- **tunnelKeeper v0.2.0**: Rust tunnel health — now TRANSITIONAL (dromedary replaced tunnel need)
- **UFW active**: deny-by-default, allow SSH/LAN/localhost
- **Tor**: .onion hidden service provides censorship-resistant access
- **DNS exfil closed**, **supply chain locked**, **crontab restricted**, **version disclosure suppressed**

### Sovereignty — ACHIEVED

The organism IS sovereign. No external dependencies remain:

- **TLS**: dromedary ACME (was Cloudflare → Caddy chain)
- **DNS**: Porkbun registrar, direct NS (was Cloudflare NS)
- **Compute**: eastGate local (was golgi VPS + gate)
- **Proxy**: dromedary (was Cloudflare CDN + Caddy reverse proxy)
- **Git**: Forgejo primary, GitHub mirror (was K-Derm diderm relay through golgi)
- **Search**: IndexNow direct submission (was Google Search Console)
- **Federation**: Nostr + ActivityPub + RSS (was ProtonMail bridge)
- **AI**: ollama local (was external API only)
- **Tunnel**: dromedary direct (was Cloudflare Tunnel → tunnelKeeper)

### Public Surfaces (7 subdomains via dromedary)

| Surface | URL | Pages | Content |
|---------|-----|-------|---------|
| **HUD** | `primals.eco` | 167 | Organism dashboard, REEDit, data feeds |
| **sporePrint** | `sporeprint.primals.eco` | 382 | 836 research papers, science notebooks |
| **Detroit** | `detroit.primals.eco` | 600+ | Municipal investigation, FOIA, data |
| **Hypothesis** | `hypothesis.primals.eco` | 52 | Formal hypotheses, falsification |
| **Tuebor** | `tuebor.primals.eco` | 35 | State-level analysis |
| **Signal** | `signal.primals.eco` | — | Signal processing |
| **NestGate API** | `nestgate.io` | — | Content gateway |

## Quick Start

```bash
# Deploy a Node Atomic via Rust CLI
nucleus-deploy deploy --composition node --gate mygate

# Deploy VPS standard (Wave 56): zero TCP ports, UDS-only
nucleus-deploy deploy --composition nest --uds-only

# Run five-layer security validation
nucleus-deploy security --layer all

# Collect membrane telemetry
nucleus-deploy telemetry --mode all

# Emit pseudoSpore from workload
nucleus-deploy spore --workload workloads/wetspring/wetspring-16s-rust-validation.toml
```

### Agent Loop (signal_plan → signal.dispatch)

With the agent composition running, use `signal_executor.sh` to close the agent
loop — Squirrel plans, biomeOS executes:

```bash
# Plan + dispatch: natural language → atomic signals
bash deploy/signal_executor.sh "check the health of all tower primals"

# Plan only (inspect the signal plan without dispatching)
bash deploy/signal_executor.sh --plan-only "deploy a nest composition"

# Dispatch a single signal directly (bypass planning)
bash deploy/signal_executor.sh --signal tower.health

# Dry run (show what would dispatch without executing)
bash deploy/signal_executor.sh --dry-run "store this data securely"
```

See [deploy/](deploy/) for full deployment instructions.

## Phase Roadmap

### Phase 1: Covalent LAN HPC ✅ VALIDATED

17 primals on the active gate (Full NUCLEUS) with provenance pipeline.
235+ wetSpring science checks passing. Full provenance chain operational.
21 sweetGrass braids. This proves the substrate works on our hardware.

### Phase 2: Ionic Compute Sharing ✅ OPERATIONAL

7 gates enrolled (5 OPEN, 1 RISEN, 1 DORMANT). LAN topology stable.
Two-house architecture with 10G fiber backbone. dromedary serves direct.

### Phase 3: Self-Hosted sporePrint ✅ COMPLETE (Wave 200)

dromedary (Pure Rust) serves 7 subdomains with ACME TLS. 1,200+ pages live.
Cloudflare FULLY DEPRECATED. Caddy DEPRECATED. No VPS needed. No proxy chain.
songBird transport available. WireGuard DISABLED (not needed — LAN direct).
Tor hidden service on eastGate. RSS self-publication. Nostr federation.
IndexNow search submission. REEDit unified surface.

**This phase is the sovereignty achievement.** The organism serves itself.

### Phase 4: Full NUCLEUS Desktop Substrate (ACTIVE)

biomeOS orchestrates across all gates. Messaging through Nest Atomic (not Stalwart).
songBird SMTP listener for inbound email → nestGate CAS → sweetGrass braids.
Metallic bonding for institutional HPC. All gardens products on NUCLEUS.
sunCloud metabolic economics. House 2 extension via TP-Link JetStream.
northGate discovery. sporeGate re-enrollment when traveling node returns.

See [PHASES.md](PHASES.md) for detailed phase architecture.

## Repo Structure

Root workspace `Cargo.toml` unifies 4 Rust crates (edition 2024, `unsafe_code = "forbid"` workspace-wide):

```
Cargo.toml          Root workspace — darkforest, tunnelKeeper, nucleus-deploy, nucleus-primals
specs/              NUCLEUS operational specs (15 active, 5 pending wateringHole migration — see specs/AUDIT.md)
gates/              Gate inventory and hardware configs
genomeBin/          Binary packaging manifest + harvest script (17 primals)
graphs/             19 deploy graph TOMLs — curated from primalSpring + gate-specific + application compositions
deploy/             Deployment tooling (CORE)
  nucleus-deploy/   Rust binary: 9 subcommands (security, provenance, deploy, spore, telemetry, summary, verify, provision, dns)
  nucleus-primals/  Shared primal registry crate — slug/env/port/composition mappings (12 tests)
  nucleus_config.sh Gate-agnostic config (converging with nucleus-primals registry)
  forgejo_mirror.sh Forgejo org/repo creation + relay push
  gate_watchdog.sh  Membrane health monitor
  gate_switch.sh    Migrate compute services between gates
  pappuscast/       DEPRECATED — see pappuscast/DEPRECATED.md
  observer_server.py DEPRECATED — vestigial static HTTP server
  legacy/           FOSSILIZED — see legacy/FOSSILIZED.md
validation/         Security validation (CORE)
  darkforest/       Pure Rust security validator (v3.0 — inner + outer membrane, 14 modules, 149 tests)
  tunnelKeeper/     Rust crate for tunnel health (Cloudflare v0.1 + Songbird v0.2, TRANSITIONAL)
  baselines/        Tunnel metrics + membrane telemetry
  archive/          Timestamped provenance runs, prior security scans
infra/              Infrastructure tooling
  ci/               Forgejo CI: runner provisioning, workflow templates, activation runbook
  benchScale/       Sovereignty parity framework
docs/               NUCLEUS primer (architectural models pending wateringHole migration — see docs/HANDOFF.md)
workloads/          PENDING HANDOFF to spring repos — see workloads/HANDOFF.md
whitePaper/         PENDING HANDOFF to primalSpring — see whitePaper/HANDOFF.md
notebooks/          PENDING HANDOFF to primalSpring — see notebooks/HANDOFF.md
```

## Handoff Status (Wave 200+)

| Component | Status | Notes |
|-----------|--------|-------|
| `workloads/` (43 TOMLs) | PENDING HANDOFF | Spring repos / primalSpring |
| `docs/BONDING_MODELS.md` | PENDING HANDOFF | wateringHole foundations |
| `whitePaper/baseCamp/` | PENDING HANDOFF | primalSpring docs |
| `deploy/pappuscast/` | **DEPRECATED** | Absorbed by sporePrint + biomeOS |
| `deploy/legacy/` (16 scripts) | **FOSSILIZED** | Bash → Rust evolution complete |
| `nucleus-primals` registry | **EVOLVING** | 13→17 primals, add dromedary/sourDough/bingoCube/swarmVine |
| `tunnelKeeper` | **TRANSITIONAL** | dromedary replaced tunnels; archive after cleanup |
| `cellMembrane` ops repo | **DEPRECATED** | golgi DOWN, eastGate runs everything |

## Core Components (refined scope)

| Component | Role | Status |
|-----------|------|--------|
| **nucleus-deploy** | Gate ops CLI: deploy, security, provenance, telemetry, DNS, provision, verify, spore | **CORE** |
| **darkforest** | Adversarial security validator (inner + outer membrane, 149 tests) | **CORE** |
| **tunnelKeeper** | Tunnel health — TRANSITIONAL (dromedary replaced need) | **ARCHIVE PENDING** |
| **nucleus-primals** | Compiled slug/port/framing registry (17 primals) | **EVOLVING** |
| **gates/*.toml** | Gate hardware + composition manifests | **CORE** |
| **graphs/** | Deploy graph TOMLs (curated from primalSpring) | **CORE** |
| **specs/** (15 operational) | NUCLEUS validation results, baselines, evolution tracking | **CORE** |
| **infra/ci/** | Forgejo CI for this repo | **CORE** |
| **infra/benchScale/** | Sovereignty parity framework | **CORE** |
| **genomeBin/** | Binary packaging manifest | **CORE** |

## Relationship to Other Repos

| Repo | Org | Relationship |
|------|-----|-------------|
| **primalSpring** | syntheticChemistry | Upstream — composition patterns, scenarios, workload standards |
| **plasmidBin** | ecoPrimals/infra | Binary depot — genomeBins fetched by nucleus-deploy |
| **wateringHole** | ecoPrimals/infra | Standards — normative specs |
| **sporePrint** | ecoPrimals/infra | Website — 382 pages, 836 papers, sovereign via dromedary |
| **projectFOUNDATION** | gardens | Knowledge foundation — validated lineage, domain threads |
| **helixVision** | gardens | Genomics product — runs on NUCLEUS substrate |
| **esotericWebb** | gardens | Creative product — runs on NUCLEUS substrate |
| ~~cellMembrane~~ | ~~gardens~~ | **DEPRECATED** — golgi VPS DOWN, eastGate runs everything |
