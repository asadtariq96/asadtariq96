# Asad Tariq

Backend engineer in Finland. Most of what I build is a service sitting in front of an API that was
never documented, and the interesting part is nearly always the same: work out the wire format,
write it down properly, then write the client.

Go, TypeScript, Python. Postgres, Redis, Docker.

## Worth reading

**[PR Desk](https://github.com/asadtariq96/github-dashboard)** is a local pull-request work queue
for GitHub. Next.js route handlers hold the token, the browser never sees it, there is no database,
and writes are optimistic and then reconciled. It is the one I would want to talk about.

**[cc-session-search](https://github.com/asadtariq96/cc-session-search)** finds an old Claude Code
session by describing what it was about. Two-stage local retrieval: dense plus BM25, fused with
reciprocal rank, then a cross-encoder over the top fifty. No API calls, no telemetry.

**[mac-sku-prices](https://github.com/asadtariq96/mac-sku-prices)** prices every Mac mini and Mac
Studio SKU across twenty-one Finnish and EU vendors and rebuilds one table every week. Stdlib
Python collectors, one JSON per source, and a table that stays honest when a collector fails.

**[finnish-rentals](https://github.com/asadtariq96/finnish-rentals)** is two reverse-engineered
clients for the big Finnish rental sites plus a CLI that filters on free-text Finnish and dedupes
the same building when four landlords list it separately.

**[verkkokauppa-cli](https://github.com/asadtariq96/verkkokauppa-cli)** is the OpenAPI spec I wrote
for a retailer's three undocumented JSON services, and the Go CLI generated from that spec.

**[SeatFlash](https://github.com/asadtariq96/finnkino-seatmap)** shows live seat maps for every
Finnkino showtime over the next seven days, on one screen.

## Elsewhere

Open an issue on anything above. I am happy to explain any of it.
