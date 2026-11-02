# Dynamics 365 Testing Navigator

Navigate Dynamics 365 testing questions, distinguishing Finance and Operations, CRM apps and Power Apps before discussing tools or acceptance.

**For:** Dynamics 365 programme owners, business process owners and QA leads who need to clarify application boundaries.

**Decision in focus:** Which application family and business journey determine the evidence discussion?

<!-- publication:links:start -->
Live website pending publisher, rights and hosting approval. Preview locally below.
<!-- publication:links:end -->

## Start here

- [Decision guide](docs/guide.html): public-source context and original discussion questions.
- [Try the mini tool](docs/tool.html): dynamics application conversation map.
- [Sources and retrieval limitations](docs/references.html).
- [Prepare a collaboration request](docs/contact.html): local copy/download; contact pending.
- [Optional orientation skill](skills/dynamics-365-testing-navigator/SKILL.md).

Open `docs/index.html` in a browser or use the local preview:

```sh
npm run preview
```

Then open [http://127.0.0.1:4173](http://127.0.0.1:4173). No package installation is needed. Node.js 22 or later is used for the optional preview and configuration commands. The static pages also work from local files.

## What you can learn

- Avoid treating all Dynamics 365 applications as a single testing surface.
- Put RSAT and canvas-app Test Studio references in their documented scopes.
- Build a brief around a business process and its application boundaries.

The mini tool works in the browser without sign-up, cookies, analytics, external libraries, AI API calls or platform connections. Results reflect user selections or assumptions. Copying and text downloads are user initiated.

## From a useful question to a collaboration

1. Read the decision guide and official references.
2. Use the mini tool to identify what needs clarification.
3. Copy the questions you want to discuss and prepare a sanitised request.
4. Use the publisher’s approved private contact channel when configured.

A first conversation can clarify the evidence question, its scope and whether a further engagement would be useful. No qualifications, client results, team history or service commitments are asserted. Never post client context or assessment requests in public issues.

## Scope

This repository contains orientation material, a small local discussion aid and an optional assistant skill. It supplies no implementation playbook, operational test suite, platform connector, internal delivery method, customer artefact or empirical assessment. No score, certification or release approval is produced.

## Technology and maintenance

- Semantic, pre-rendered HTML; responsive CSS; browser JavaScript.
- Node.js built-in modules for local serving and publication configuration.
- Zero runtime dependencies, no lockfile required, no CI or paid service enabled.
- Entry point: `docs/index.html`; runtime: `docs/assets/tool.js`.
- Configuration: `site-config.json`; run `npm run configure` only after publication inputs are approved.
- Editorial/source review date: 2026-11-02. Recheck vendor sources before release and following a relevant vendor change.

## Search intent and GitHub discovery

Primary topic: **Dynamics 365 testing**.

Related search phrases: D365 testing readiness; Dynamics 365 regression testing; Dynamics 365 Finance Operations RSAT; Power Apps testing scope. These are editorial keyword hypotheses, not measured search-volume claims.

Suggested GitHub topics: `dynamics-365`, `d365`, `dynamics365-testing`, `power-apps`, `rsat`, `erp`, `crm`, `quality-assurance`. Use only topics describing the actual content. Repository description and topics are provided in [github-metadata.json](github-metadata.json); description and topics are configured on the private GitHub repository.

## Publication status

**Private GitHub preparation.** Repository: [dynamics-365-testing-navigator](https://github.com/mr-jonam/dynamics-365-testing-navigator). Public visibility and a website deployment have not been enabled. Public contact, domain, legal holder, final rights and hosting notice need approval. Draft pages use `noindex, nofollow` and robots exclusion. Final configuration creates canonical URLs, social metadata, structured data, robots and sitemap; it does not deploy anything. See [PUBLISHING.md](PUBLISHING.md). Use an approved hosting destination for the commercial landing site; review GitHub Pages usage limits.

## Sources and attribution

- [Microsoft Learn — Regression suite automation tool (RSAT)](https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/perf-test/rsat/rsat-overview)
- [Microsoft Learn — Test Studio](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/test-studio)

Read [SOURCES.md](SOURCES.md) for verification status. References are linked, not republished. Product names identify subject matter; no vendor affiliation, endorsement, logo or partner status is claimed.

## Licence and provenance

Provisional private-development status: **LicenseRef-Proprietary**. No public reuse licence has been granted. See [LICENSE](LICENSE), [NOTICE](NOTICE) and the per-component review in [LICENSE-DECISION.md](LICENSE-DECISION.md). Final licence selection requires the legal holder’s approval. This preview is not described as open source.

Transparent project identifiers and source/licence hashes are recorded in `.provenance/manifest.json`. Signing and encrypted identity are pending user-controlled inputs. Identifiers and hashes provide integrity/correlation evidence, not DRM or conclusive proof of ownership.
