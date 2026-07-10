<div align=center>
  <h1>📍 GEO Local Skill</h1>
  <p><em>Agent skill for local businesses: optimizes Google Business Profile + local schema for AI discovery.</em></p>
  <p><a href=LICENSE><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt=License></a>
  <p>by <a href=https://brandvirality.com>BrandVirality</a><br>
  <strong>Author:</strong> <a href=https://github.com/josezuma>Jose Zuma</a></p>
</div>

## Quick Start

```bash
pip install requests
python3 scripts/audit_local.py "Business Name" "City, State"
```

## Checks
| Check | What it verifies |
|-------|-----------------|
| GBP completeness | Name, address, phone, hours, photos |
| LocalBusiness schema | @type: LocalBusiness with geo coordinates |
| NAP consistency | Name, Address, Phone across web |
| Review schema | AggregateRating for citation potential |
| Maps citations | Presence in Google Maps, Apple Maps |

## Related
geo-audit-skill, schema-for-ai, ai-crawlers, awesome-ai-visibility
