# Contributing Guidelines

Thanks for helping improve **Awesome Mechatronics**. Every addition, correction and dead-link report is appreciated.

## What belongs here

This list covers mechatronics as an engineering discipline: the co-design of mechanism, actuation, sensing, computation and control policy — classical *and* learned.

Good additions are resources a working mechatronic engineer or student would be glad someone pointed them to.

Please **keep the mechatronic point of view**. This is not a general AI list, a general mechanical-engineering list, or a general electronics list. A resource that is only about one of those domains, with no bearing on integrated physical systems, belongs in one of the [related lists](README.md#14-related-awesome-lists) instead.

## Entry format

Add entries to the bottom of the relevant subsection, one per line:

```markdown
- 🔧 [Resource Name](https://example.com) — one line on why it is worth someone's time. 🆓
```

For entries inside a table, match the columns of the surrounding table.

### Markers

Use the same markers as the README legend:

| Marker | Meaning | Marker | Meaning |
|---|---|---|---|
| 📖 | book | 🧪 | hands-on |
| 📄 | paper | 🆓 | free / open source |
| 🎓 | course | 💵 | paid |
| 🔧 | tool | ⭐ | start here if you're new |
| 📝 | write-up | 🔬 | research-level |

Every entry should carry a type marker (📖 📄 🎓 🔧 📝) and a cost marker (🆓 or 💵) where cost is meaningful. Use ⭐ sparingly — it means "the one to read first in this subsection".

### Style rules

- **Prefer free and open resources**; mark paid ones with 💵.
- **Prefer primary sources** — papers, official documentation, project repositories — over blog summaries and aggregator pages.
- **Include the year** for anything in the fast-moving sections (§7 Learning-Based Control, §8 Agentic AI, §12 Trends Radar) so readers can judge staleness.
- **Say why in one line.** "It's good" is not a reason. Name what the resource teaches or what problem it solves.
- Use [title casing](http://titlecapitalization.com) (AP style) for names; sentence case for descriptions.
- Use an em dash (—) between the link and its description, matching the surrounding entries.
- British spelling is used throughout (*optimisation*, *behaviour*, *modelling*). Please match it.
- Link directly to the resource, not to a redirect, tracker or paywall proxy.
- No links to illegally distributed copies of books or papers.

## Before opening a pull request

- Search existing entries and open pull requests — yours may be a duplicate.
- Check the resource is still maintained and still reachable.
- One pull request per suggestion, with a useful title.
- The body of your commit message should contain a link to the resource you are adding.
- Check spelling and grammar, and make sure your editor strips trailing whitespace.
- New categories, and improvements to the existing categorisation, are welcome — if you add a section, add it to the table of contents as well.

## Corrections and removals

Dead links, superseded standards, renamed projects and stale "current state" tables (the ROS 2 distro table, §12 Trends Radar) are all worth a pull request on their own — these age fastest and are the most useful thing to fix.

Prefer **updating** an entry over deleting it. If a resource is outdated but historically important, keep it and say so in its description.

## Diagrams

The three diagram SVGs in [`assets/`](assets/) — the stack, the definition timeline and the classical-vs-learned pipeline — are plain hand-written SVG: no external fonts, no embedded rasters, no build step. Open one in a text editor to change wording. (`mechatronics-venn.svg` is the older Inkscape drawing and has no background rectangle, so it needs one before it reads well on dark backgrounds.) Mermaid diagrams are inline in the README so they stay diffable in pull requests.

Use Mermaid when a diagram is structural and likely to be edited by contributors; use SVG when layout, density or typography matters.

## Licence

By contributing, you agree that your contributions are released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), like the rest of this list.

---

**Finally** — every link and contribution, no matter how small, is highly appreciated and encouraged. It helps gather all the resources in one place.
