<div align=center>
  <h1>📍 GEO Local Skill</h1>
  <p><em>Agent skill for local businesses: optimizes Google Business Profile + LocalBusiness schema + maps citations for AI discovery.</em></p>
  <p><a href=LICENSE><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt=License></a>
  <a href=https://github.com/josezuma/geo-local-skill/actions/workflows/ci.yml><img src="https://img.shields.io/badge/CI-passing-green.svg"></a></p>
  <p>by <a href=https://brandvirality.com>BrandVirality</a> — <strong>SaaS for AI visibility.</strong><br>
  <strong>Author:</strong> <a href=https://github.com/josezuma>Jose Zuma</a></p>
</div>

---

## Quick Start

```bash
pip install requests beautifulsoup4
python3 scripts/audit_local.py "Business Name" "City, State"
```

## What It Checks

| Category | Weight | What It Verifies |
|----------|:------:|-----------------|
| Google Business Profile | 30 pts | Name, address, phone, hours, website, photos, categories |
| LocalBusiness Schema | 25 pts | @type: LocalBusiness with geo coordinates, opening hours |
| NAP Consistency | 20 pts | Name, Address, Phone match across web directories |
| Review Schema | 15 pts | AggregateRating markup for AI citation potential |
| Maps Citations | 10 pts | Presence in Google Maps, Apple Maps, Bing Maps |

## Scoring

| Score | Meaning |
|:-----:|---------|
| 90-100 | Excellent — fully optimized for local AI search |
| 70-89 | Good — minor gaps (add missing schema or reviews) |
| 50-69 | Needs work — missing key local signals |
| 0-49 | Poor — invisible in local AI search |

## Why Local GEO Matters

When someone asks ChatGPT or Perplexity "find a plumber in Austin" or "best coffee shop near me", the response draws from:

1. **Google Business Profile data** (name, address, phone, hours, reviews)
2. **LocalBusiness schema** on the website (geo coordinates, opening hours, payment methods)
3. **Review schema** (AggregateRating with review count and average)
4. **NAP consistency** (identical name, address, phone across the web)
5. **Maps citations** (Google Maps, Apple Maps, Bing Maps listing presence)

Without these signals, local businesses are invisible in AI-generated local search results.

## Related

- [schema-for-ai](https://github.com/josezuma/schema-for-ai) — JSON-LD templates
- [geo-audit-skill](https://github.com/josezuma/geo-audit-skill) — URL-level GEO audits
- [ai-crawlers](https://github.com/josezuma/ai-crawlers) — Check which AI crawlers hit your site
- [awesome-ai-visibility](https://github.com/josezuma/awesome-ai-visibility)
- [+15 more AI visibility repos](https://github.com/josezuma?tab=repositories)

## License

[MIT](LICENSE) © 2026 [Jose Zuma](https://github.com/josezuma) / [BrandVirality](https://brandvirality.com)
