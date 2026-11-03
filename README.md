# Coronado Happenings

A hyperlocal community publication for Coronado: what is happening, who is doing
it, and what it means for people who live here.

**Status: in development — planning and structure only.** No public build exists,
and no verified working software is published here.

This repository is a **public project showcase**. It documents purpose, design
intent and direction. The implementation, operational configuration and editorial
tooling are developed in a private repository and are not published here.

---

## Why it exists

Local news has thinned out everywhere, and the gap is filled by screenshots of
screenshots. A small community publication can do something a large one cannot:
know the street, name the organisation, correct itself quickly, and show its work.
Coronado Happenings asks: **what is the smallest publishing system that a
community can actually sustain — cheap to run, pleasant to read, and honest about
its sources?**

## Design direction

These are intentions, not a description of finished software.

### Reading: continuous, not paginated

The reading surface is designed around an endless-scrolling stream rather than
page numbers, so a reader can move from today's items into the archive without
losing their place. Continuous scrolling is a design constraint with real costs —
retaining position, keeping the URL honest, avoiding runaway data use — and those
costs are treated as requirements rather than as polish to skip.

### Ingestion: structured, attributed, human-gated

- Contributions and submissions enter through a defined ingestion path, with the
  originating source and submitter recorded.
- Machine-assisted collection is labelled as such and never silently presented as
  editorial judgement.
- Publication is a human editorial decision. Automated agents may propose; a
  person publishes.

### Advertising: prospective, and explicitly separate

Local advertising is a plausible way for a publication like this to pay for
itself. It is treated here as a **prospective** system: clearly separated from
editorial content, labelled as advertising, with no behavioural targeting of
readers and no reader profiles sold. Any advertising system described in this
project is a plan, not a live product.

## What works today

Nothing verifiable. There is no public deployment, no released build, and no
editorial archive. This showcase records the concept and its boundaries while the
private development repository holds a labelled scaffold.

## Planned milestones

| Milestone | State |
|---|---|
| Product definition: sections, ingestion rules, editorial gate | Documented |
| Private development scaffold | Initialised |
| Endless-scroll reading surface | Planned |
| Attributed ingestion pipeline | Planned |
| Editorial review queue | Planned |
| Advertising system (prospective) | Concept only |
| Public preview build | Not scheduled |

## Boundaries

- **Operational configuration, unpublished submissions, private analytics and
  contributor correspondence are not published here.**
- No advertising system is live, and no advertiser or reader data is collected
  by this project today.
- No third-party photographs, articles or submissions are redistributed here
  without documented permission.

## Intended audience

Coronado residents, local organisations and event organisers, and small-publisher
engineers interested in sustainable hyperlocal publishing.

## Related projects

Other public projects in this portfolio:

- [LegacyOS](https://github.com/DanUrtnowski/LegacyOS) — a modern environment for old x86 hardware
- [MuseForge](https://github.com/DanUrtnowski/MuseForge-Showcase) — real-instrument music learning
- [Open E-Reader](https://github.com/DanUrtnowski/Open-E-Reader) — a free, offline-first reader
- [Secure Browser](https://github.com/DanUrtnowski/Secure-Browser) — a privacy-oriented browser concept
- [Whale Intelligence Network](https://github.com/DanUrtnowski/Whale-Intelligence-Network) — whale and dolphin research intelligence
- [Power Line News](https://github.com/DanUrtnowski/Power-Line-News) — utility infrastructure accountability
- [Immigration Law & Intelligence](https://github.com/DanUrtnowski/Immigration-Law-Intelligence) — official-record legal intelligence
- [Voalt](https://github.com/DanUrtnowski/Voalt) — the network that connects these projects

Portfolio profile: [DanUrtnowski](https://github.com/DanUrtnowski)

## Scope and licensing

This is a **showcase repository** containing documentation only:

- No implementation source code is published here.
- **No open-source licence is granted** for the private implementation.
- Editorial content, once it exists, will carry its own rights statement; nothing
  published here grants reuse rights for it.

See [CHANGELOG.md](CHANGELOG.md) for the public milestone record.
