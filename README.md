# Week 09: Application Design Patterns

A three-hour graduate computer science lecture organized around:

**Pattern -> problem -> real product case -> implementation walkthrough -> benefits and trade-offs.**

## Lecture materials

| Format | File |
|---|---|
| PowerPoint with editable diagrams and speaker notes | [Download the slide deck](Application-Design-Patterns-Revised.pptx) |
| Self-contained HTML presentation | [Download the HTML deck](Application-Design-Patterns-Revised.html) |
| Markdown lecture and instructor notes | [Read the lecture](Application-Design-Patterns-Revised.md) |
| All formats and diagram assets | [Download the complete bundle](Application-Design-Patterns-Revised-Bundle.zip) |

Download the HTML file and open it in a browser. Use the arrow keys or Space to
navigate, **N** for instructor notes, and **F** for fullscreen. The presentation
works offline; external source links require an internet connection.

Keep the `diagrams` directory beside the Markdown file when downloading the notes,
or extract the complete bundle.

## Topics and cases

- Monolith and modular monolith: Shopify.
- Microservices: Netflix's migration and service-isolation patterns.
- Event-driven architecture: LinkedIn's shared data backbone.
- CQRS: Netflix Tudum's original design, stale previews, and revised implementation.
- Distributed cache hierarchy: Facebook TAO.
- CDN and edge delivery: Netflix Open Connect.
- Online recommendation pipelines: TikTok's public product behavior and the
  separately documented ByteDance/BytePlus Monolith system.

The schedule includes two ten-minute breaks and a synthesis activity. Optional
appendices cover Discord request coalescing, global deployment, operational
concerns, and sources. DNS, firewalls, private networks, CDN behavior, replication,
and recovery are discussed alongside the application patterns.

Company architectures are dated, simplified case studies rather than assertions
about complete current production systems. Reported outcomes and teaching
reconstructions are distinguished in the lecture notes.
