# Permaculture-DAO

Permaculture-DAO is the canonical development home of the Prometheus ecosystem.

Prometheus should be understood, at system level, as a candidate regenerative
transformation architecture whose capital-facing use remains gate-dependent.

The organization maintains the active Prometheus v1.1 Genesis Institutional Canonical Line and the bounded pilot implementation stack.

## Current canonical line

Current canonical line:

**Prometheus v1.1 — Genesis Institutional Canonical Line**

Primary canonical repository:

**[Permaculture-DAO/prometheus-canon](https://github.com/Permaculture-DAO/prometheus-canon)**

Public signed-release registry:

**[Permaculture-DAO/prometheus-canonical-releases](https://github.com/Permaculture-DAO/prometheus-canonical-releases)**

Current public releases:

- canonical: `v1.1.2-genesis`;
- bounded synthetic runtime proof: `v1.1.3-runtime-proof`.

Prometheus v1.1 is not treated as a patch, continuation, or automatic upgrade of any previous Prometheus repository, release, hash set, signature set, runtime artifact, or development archive.

Pre-v1.1 materials are historical development artifacts unless explicitly reintroduced through the v1.1 signed canonical release process.

## Source-of-truth hierarchy

Prometheus is maintained through a strict separation of institutional meaning, canonical documentation, repository scope, implementation behavior, and runtime execution.

The hierarchy is:

1. White Paper — defines the current institutional architecture of Prometheus.
2. prometheus-canon — preserves the active canonical Genesis line, review materials, verification procedures, checksum discipline, signing workflow, and governance boundary.
3. Repository README files — define repository-specific scope and operational boundaries.
4. Runtime code — implements bounded pilot behavior.
5. Deployment and operations documentation — governs execution, troubleshooting, and runtime discipline.

Runtime code, repository documentation, dashboards, API responses, token interfaces, or operational scripts must not silently redefine the constitutional intent of the White Paper or prometheus-canon.

## Core repositories

The public repositories are the canon, the signed-release registry, the
bounded Holochain runtime, and the development runtime candidate. Other Genesis
repositories remain private pilot workspaces until their own publication,
licensing, privacy, and release gates are cleared.

### prometheus-canonical-releases

Minimal public cryptographic registry for signed canonical release sets,
manifests, checksums, public keys, and verification instructions. Historical
development freezes remain in a separate private archive and do not silently
become current canon.

### prometheus-canon

Primary canonical source repository for the Prometheus v1.1 Genesis Institutional Canonical Line.

This repository contains the canonical White Paper, canonical Markdown derivatives, verification documentation, staging audit, governance boundary, reproducible release procedures, checksum workflow, and signing discipline.

It is the active canonical source of truth for the v1.1 Genesis line.

### prometheus-runtime

Public development runtime candidate for the bounded Prometheus pilot: gated
data ingestion, normalization, and evidence batch packaging, staged behind an
`S0`-`S6` freeze/rotate/publication discipline. Development status only;
production, legal, and market admission remain gated. Runtime execution does
not redefine Prometheus constitutional meaning.

### prometheus-happ

Public Holochain-native implementation repository for the bounded Prometheus
pilot backend and signed synthetic runtime proof.

This repository contains the bounded pilot runtime implementation layer:

- DNA;
- integrity zomes;
- coordinator zomes;
- pilot backend logic;
- Holochain-native runtime behavior;
- source-chain-based records;
- validation-bound data structures.

The hApp implements pilot behavior. It does not redefine Prometheus constitutional meaning.

### prometheus-bridge

Bridge layer for the Prometheus pilot runtime.

This repository exposes the application-facing HTTP/API layer in front of the Holochain websocket path and may support pilot-facing runtime endpoints such as:

- /health
- /list_messages
- /set_message

The bridge is an interface layer. It does not create PRU value, token rights, investor rights, land rights, or governance authority.

### prometheus-console

Frontend console repository for the Prometheus pilot.

This repository contains the public-facing application UI intended to connect to the Prometheus bridge and runtime stack.

The console makes pilot data legible. It does not independently validate ecological claims or authorize capital-facing representations.

### prometheus-ops-docs

Operational SOPs, runbooks, troubleshooting, local runtime instructions, deployment discipline, incident handling, and operator procedures for the pilot stack.

### prometheus-evaluation-stack

Evaluation and gating stack for Prometheus pilot outputs.

This repository supports scoring, reporting, validation logic, QA checks, and GO / NO_GO / MANUAL_REVIEW decisioning.

Its function is not to create financial value automatically. Its function is to support disciplined evaluation before claims, deployment, reporting, or capital-facing interpretation advance.

### prometheus-pilot-handoff-pack

Canonical developer handoff repository for the Prometheus Rigenera pilot.

This repository contains implementation-facing context, pilot boundaries, operating assumptions, handoff notes, data-room readiness, and deployment sequence.

### prometheus-mock-backend

Executable behavioral specification for the Prometheus pilot backend.

This repository preserves expected backend behavior before or alongside full Holochain-native implementation.

## Canonical ontology

Prometheus v1.1 defines Prometheus as verified regenerative infrastructure, not a public offering and not a token-first system.

The operative ontology is:

- OHE generates regenerative performance;
- MRV and provenance make evidence reviewable;
- PRU provides the value-analysis and maturity-classification interface;
- RAP aggregates verified units into portfolio-grade regenerative infrastructure;
- TRBK supports governance, coordination, access, or participation within legal boundaries;
- HoloFuel supports operational transaction and infrastructure capacity;
- any future financial or digital instrument requires a compliant legal wrapper, jurisdiction-specific review, disclosure, and investor-protection discipline.

## Verification-first discipline

Prometheus treats verification as infrastructure.

The operational sequence is:

claim → observation → evidence → provenance → integrity → verified indicator → admissibility → value

No repository in this organization should bypass that sequence.

A claim does not become value merely because it appears in a README, dashboard, token interface, API response, investor deck, runtime output, or release note.

Value becomes admissible only through evidence, methodology, confidence, governance review, legal boundaries, and appropriate structuring.

## Runtime boundary

The bounded pilot stack may implement:

- local runtime records;
- Holochain-native message behavior;
- bridge endpoints;
- frontend console views;
- mock backend behavior;
- evaluation gates;
- operational runbooks;
- pilot handoff materials.

The bounded pilot stack must not independently implement or imply:

- investor rights;
- fractional ownership;
- land rights;
- securities;
- automatic PRU issuance;
- automatic ecological credits;
- automatic tokenized asset claims;
- automatic governance authority;
- medical claims;
- public financial representations.

Those layers require separate legal, methodological, governance, and institutional review.

## Project philosophy

Prometheus is developed with a pilot-first discipline.

This means:

- explicit scope before expansion;
- behavior before abstraction;
- validation before execution;
- evidence before claims;
- operational clarity before scale;
- implementation fidelity before architecture drift;
- MRV before PRU value analysis;
- legal structure before capital-facing instruments;
- governance review before irreversible commitments.

Prometheus does not scale by inflating narrative.

Prometheus scales by preserving coherence under real conditions.

## Legacy boundary

Pre-v1.1 repositories, releases, drafts, hashes, signatures, generated packs, runtime artifacts, and development materials are historical development artifacts.

They are not part of the active canonical release path unless explicitly reintroduced through the v1.1 signed canonical release process.

No legacy artifact may silently become canonical by being copied into a Genesis repository.

## Public entrypoints

Institutional public site:

- heart-intelligence.earth

Public source and verification:

- https://github.com/Permaculture-DAO/prometheus-canon
- https://github.com/Permaculture-DAO/prometheus-canonical-releases
- https://github.com/Permaculture-DAO/prometheus-happ
- https://github.com/Permaculture-DAO/prometheus-runtime

Planned application and bridge entrypoints for the Prometheus pilot stack:

- app.heart-intelligence.earth
- api.heart-intelligence.earth

## Founder

Canonical project development lives under the Permaculture-DAO organization.

Prometheus and the h•eart•h intelligence initiative were founded by Uwohali.
