# system-design-notes

Portfolio-quality system design notebook by [Sumit Kumar Ta](https://github.com/SK090347).

Markdown-first notes with Mermaid diagrams: requirements → APIs → data model → scaling trade-offs. Written like a working engineer’s design journal — ambitious and rigorous, not a dump of interview scripts.

## Index

| Note | Focus |
|------|--------|
| [URL Shortener](./notes/url-shortener.md) | Encoding, redirects, sharding, analytics |
| [Rate Limiter](./notes/rate-limiter.md) | Token bucket, sliding window, distributed coordination |
| [News Feed](./notes/news-feed.md) | Fan-out, ranking, timeline storage |
| [Campus OS Knowledge Layer](./notes/campus-os-knowledge-layer.md) | Campus knowledge graph / retrieval layer (conceptual CampusOS-aligned design) |

## How to read these notes

1. **Problem & goals** — functional + non-functional requirements  
2. **High-level design** — Mermaid diagrams for components and flows  
3. **Deep dives** — storage, consistency, failure modes  
4. **Trade-offs** — what I’d ship first vs. what scales later  

## Principles

- Prefer clear APIs and measurable SLOs over buzzwords  
- Call out consistency, failure, and cost explicitly  
- Diagrams live *in* the markdown (Mermaid) so reviews stay in git  

## Contributing

Light guidelines in [CONTRIBUTING.md](./CONTRIBUTING.md). Issues and PRs welcome for clarifications and alternative designs.

## License

MIT © Sumit Kumar Ta

## License

Documentation licensed under [CC BY 4.0](./LICENSE).
