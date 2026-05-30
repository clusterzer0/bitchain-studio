# bitchain-studio

> **Retired 2026-05.** This product has been dissolved into **Quickring Courier** (QR-20).

bitchain-studio was originally planned as a standalone desktop and mobile GUI for creating and managing [bitchain](https://github.com/clusterzer0/bitchain) bundles — a visual interface over the bitchain CLI for non-technical users.

The capabilities that bitchain-studio was meant to deliver (visual file browser, storage backend configuration, manifest inspection, bundle history) are now part of **Quickring Courier**, the consumer file-sharing app under the Quickring brand. Courier ships these capabilities in the context of family-coordination file sharing rather than as a standalone bitchain tool — which is the right framing for a consumer-facing surface.

## Where it went

| Originally planned in bitchain-studio | Now in |
|---|---|
| Visual file browser for ingesting files into bundles | Quickring Courier (QR-20) |
| Storage backend configuration (S3, HTTP, local) | Refraction (CLUS-2) for enterprise; Cumulus's local block store (DEV-30) for households |
| Manifest inspector | Quickring Courier + Refraction's web UI |
| Cross-platform desktop / mobile | Flutter, via Quickring Courier |

## References

- **Quickring Courier** — `quickring/courier`, Jira epic QR-20
- **bitchain CLI** — `clusterzer0/bitchain`, the canonical CLI surface that remains
- **Refraction** — `clusterzer0/refraction`, the enterprise web surface for bitchain
- `softsurve/sol/weekly/2026-05-clusterzer0-quickring-review.md` — the May-2026 record explaining the dissolution

## License

N/A — retired before active code shipped.
