# seo-geo: one Claude Code skill for classic and AI search

A single skill for getting pages found, understood, ranked and cited: technical SEO, Core Web Vitals,
content and intent, schema, AI search (Google AI Overviews and AI Mode, ChatGPT search, Perplexity,
Gemini, Copilot, Claude), AI crawlers, llms.txt, entity signals, local SEO, hreflang, programmatic
pages, audits and measurement, plus a reference for Lithuanian sites.

It replaces a pile of overlapping seo-*, geo-*, aeo and schema skills with one set of rules. Where the
sources disagreed or quoted unverified statistics, this skill picks one rule and labels claims as
claims.

## Install

```sh
git clone https://github.com/P1tak4s/seo-geo-skill.git
cp -r seo-geo-skill/seo-geo ~/.claude/skills/
```

Or get it bundled in the [pilot](https://github.com/P1tak4s/pilot) plugin.

## Structure

```
seo-geo/
  SKILL.md                operating manual: rules, workflow, key numbers
  references/
    technical.md          crawl, index, canonicals, redirects, JS rendering, sitemaps, CWV, images
    content.md            intent, E-E-A-T, on-page, briefs, clusters, internal links, comparison and shop pages
    schema.md             JSON-LD rules, what still earns rich results, core patterns
    ai-search.md          citable passages, AI crawlers and robots.txt, llms.txt, entities, platforms, tracking
    local.md              Google Business Profile, reviews, NAP, location pages
    international.md      hreflang, translations, locale formats
    programmatic.md       gates and build rules for template pages
    agent-readiness.md    Is Agentic checks: how to run, what each check needs, fix order
    audit.md              audit flow, priorities, backlinks, GSC/GA4/CrUX, regression watch
    lithuania.md          Lithuanian copy, slugs, schema fields, directories, AI search in LT
```

## Credits

Rules are rewritten and merged in my own words from these open-source projects; use them for depth:

- [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) (MIT): audits, technical, hreflang, images, schema deprecations, local, programmatic gates, clusters
- [zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude): GEO citability, AI crawlers, llms.txt, brand mentions, platform notes
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) and [aeo-box](https://github.com/alirezarezvani/aeo-box): AEO and citation patterns
- Community skills for SEO fundamentals, schema markup, programmatic SEO and site architecture
- [Is Agentic](https://is-agentic.com) methodology and report API
- Google Search Central documentation

## License

MIT
