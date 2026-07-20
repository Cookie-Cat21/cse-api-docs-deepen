# CSE (cse.lk) API — deepen pack

> Unofficial live-probed API documentation.
> **Not affiliated** with the upstream operator. Data may change without notice.

**Tier:** A · **Category:** markets · **Status:** extend-existing

Deepen Cookie-Cat21/cse-api-docs with topGainers, topLooses, 52WeekSectors, company announcements, GICS valuations.

Pattern siblings: [cse-api-docs](https://github.com/Cookie-Cat21/cse-api-docs) · [ikman-api-docs](https://github.com/Cookie-Cat21/ikman-api-docs)

## Research

Research staged in [ArdenoStudio/lankawa](https://github.com/ArdenoStudio/lankawa) `api-docs/packages/cse-api-docs-deepen/`. Source docs:

- `docs/CSE_API_DOCS.md`
- `docs/CSE_UNUSED_ENDPOINTS_PROBE.md`

## Layout

```
catalog/endpoints.yaml
samples/
scripts/probe.py
scripts/build_site.py
docs/ETHICS.md
examples/
python/
site/
```

## Quick start

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python scripts/probe.py
python scripts/build_site.py
```

## Clients

- Python: [`python/`](./python/) — `cse-api-docs-deepen-unofficial` (`pip install -e .`)
- TypeScript: [`typescript/`](./typescript/) — `@cookie-cat21/cse-api-docs-deepen-client`
- JavaScript (ESM, no build): [`javascript/`](./javascript/) — `client.mjs`

## License

MIT for docs/harness. Upstream data remains subject to upstream terms.
