# Technology Stack Analysis: Phoenix Plumbing Market

**[Back to Main Report](./README.md)**

---

## Executive Summary

Analysis of 93 competitor websites reveals a **dominant Angular pattern** across 91% of sites, suggesting widespread use of a common booking platform, chat widget, or regional agency. This creates a structural performance vulnerability that can be exploited.

| Finding | Implication |
|---------|-------------|
| 91% use Angular | Shared platform/vendor dependency |
| Angular sites avg 61.1 mobile score | 6 points below non-Angular |
| Angular sites avg 10.4s LCP | 3 seconds slower than non-Angular |
| GoDaddy sites outperform all others | Simple templates beat overengineered sites |

---

## Platform Performance Comparison

### By CMS Platform

| Platform | Sites | Avg Mobile | Avg Desktop | Avg LCP | Avg Reviews |
|----------|-------|------------|-------------|---------|-------------|
| GoDaddy Website Builder | 5 | **77.4** | 92.4 | 4,721ms | 80 |
| WordPress (no version) | 19 | 65.5 | 79.4 | 8,820ms | 889 |
| Wix | 4 | 64.8 | 86.3 | 7,467ms | 133 |
| Unknown/Custom | 43 | 62.2 | 78.5 | 9,106ms | 1,333 |
| Webflow | 1 | 60.0 | 93.0 | 12,029ms | 39 |
| WordPress 6.9 | 12 | 55.3 | 69.8 | 15,409ms | 286 |
| Squarespace | 5 | **44.8** | 62.2 | 16,461ms | 168 |

**Key Insight:** GoDaddy's simple templates outperform sophisticated platforms. Squarespace sites have the worst mobile performance despite being marketed as "modern."

### By JavaScript Framework

| Framework | Sites | Avg Mobile | Avg LCP |
|-----------|-------|------------|---------|
| Angular Only | 76 | 61.2 | 10,211ms |
| jQuery/Other | 9 | 64.0 | 8,341ms |
| Vue.js | 8 | 60.4 | 11,913ms |

**Key Insight:** Framework choice matters less than implementation quality. However, Angular's ubiquity (91%) suggests a common external dependency.

---

## Angular Sites Analysis

### Why Is Angular Everywhere?

91% of competitor sites include Angular. This is not organic adoption - local plumbers don't choose JavaScript frameworks. Likely causes:

1. **ServiceTitan / Housecall Pro widgets** - Booking and chat systems often inject Angular
2. **Scorpion / LSA agencies** - Large home services marketing agencies standardize on Angular
3. **Regional web agency** - One dominant agency may serve many Phoenix plumbers

### Performance Distribution

| Mobile Score Range | Angular Sites | % of Angular |
|--------------------|---------------|--------------|
| Poor (0-49) | 26 | 31% |
| Needs Improvement (50-79) | 42 | 50% |
| Good (80-100) | 16 | 19% |

**71% of Angular sites fail to achieve "Good" mobile performance.**

### Worst Performing Angular Sites

| Company | Mobile | LCP | Reviews | Opportunity |
|---------|--------|-----|---------|-------------|
| Drain Squad | 26 | 17.0s | 42 | Beat easily |
| Roto-Rooter | 33 | 6.1s | 315 | National brand, local weakness |
| Deer Valley Plumbing | 34 | 16.0s | 41 | Geographic overlap |
| Amigo Rooter | 35 | 9.0s | 584 | Established but vulnerable |
| **American Home Water & Air** | 35 | 7.8s | 2,950 | Major player, terrible mobile |
| Parker & Sons | 44 | 26.2s | 31,728 | Market leader, slowest site |

**Strategic Opportunity:** The top 2 players (Parker & Sons, American Home Water & Air) both have terrible mobile scores. A challenger with 80+ mobile score would outperform them technically.

### Best Performing Angular Sites

| Company | Mobile | LCP | Reviews |
|---------|--------|-----|---------|
| Armstrong Plumbing | 100 | 756ms | 284 |
| Blackstone Plumbing | 100 | 1,771ms | 157 |
| PlumbSmart | 99 | 1,651ms | 262 |
| Darrels Drain Cleaning | 99 | 2,177ms | 41 |
| Sunstate Plumbing | 95 | 962ms | 104 |

**Proof:** Angular doesn't guarantee poor performance. These sites prove it's possible to use Angular and still achieve excellent scores. The difference is implementation quality.

---

## WordPress Sites Analysis

### Overview

34 sites use WordPress (37% of market). Performance varies dramatically based on version and theme.

| WordPress Version | Sites | Avg Mobile | Avg LCP |
|-------------------|-------|------------|---------|
| Version unknown | 19 | 65.5 | 8,820ms |
| 6.9 | 12 | 55.3 | 15,409ms |
| 6.8.3 | 1 | 39.0 | 27,738ms |
| 6.7.4 | 1 | 47.0 | 12,047ms |
| 5.5.17 | 1 | 65.0 | 6,212ms |
| 4.9.3 | 1 | 47.0 | 8,540ms |

**Paradox:** Newer WordPress versions (6.8, 6.9) perform worse than older versions. This is likely due to heavy themes and plugins added during updates, not the core software.

### WordPress Site Roster

| Company | WP Version | Mobile | Reviews | Notes |
|---------|------------|--------|---------|-------|
| Edge Plumbing | 6.8.3 | 39 | 29 | Worst WP site |
| All Drains Emergency | 6.7.4 | 47 | 186 | Below average |
| Proforce Plumbing | 5.5.17 | 65 | 75 | Old version, decent perf |

---

## Squarespace Sites Analysis

### Overview

5 sites use Squarespace - and they're the **worst performing segment**.

| Company | Mobile | Desktop | LCP | Reviews |
|---------|--------|---------|-----|---------|
| Average | 44.8 | 62.2 | 16,461ms | 168 |

**Warning:** Squarespace is marketed as "beautiful and easy" but delivers terrible mobile performance. Any Squarespace competitor is vulnerable.

---

## GoDaddy Sites Analysis

### Overview

5 sites use GoDaddy Website Builder - and they're the **best performing segment**.

| Metric | Value |
|--------|-------|
| Avg Mobile Score | 77.4 |
| Avg Desktop Score | 92.4 |
| Avg LCP | 4,721ms |

**Irony:** The "cheap" option outperforms the "professional" options. GoDaddy's constraints (simple templates, limited customization) prevent the bloat that kills performance on other platforms.

---

## Strategic Recommendations

### For New Market Entrants

1. **Avoid Squarespace** - Worst mobile performance in the market
2. **If using WordPress** - Choose lightweight theme, minimize plugins, optimize images
3. **If using Angular booking widgets** - Lazy load them (don't block render)
4. **Target 80+ mobile score** - Puts you in top 19% of market
5. **Target <3s LCP** - Puts you ahead of 90%+ of competitors

### Competitive Positioning by Platform

| Competitor Platform | Your Advantage |
|--------------------|----------------|
| Squarespace (44.8 avg mobile) | Any optimized site beats them |
| WordPress 6.9 (55.3 avg mobile) | Lightweight site wins |
| Angular (61.1 avg mobile) | Clean implementation wins |
| Parker & Sons (44 mobile, 26s LCP) | Basic optimization beats market leader |

### Technical Checklist

- [ ] Mobile score ≥80
- [ ] LCP ≤2.5 seconds
- [ ] No render-blocking JavaScript
- [ ] Images in WebP/AVIF format
- [ ] Lazy load below-fold content
- [ ] Minimal third-party scripts

---

## Appendix: Full Site List by Technology

### Angular Sites (84 total)

[See main report for full competitor list]

### WordPress Sites (34 total)

[See main report for full competitor list]

### Other Platforms (9 total)

- Squarespace: 5 sites
- GoDaddy: 5 sites
- Wix: 4 sites
- Webflow: 1 site

---

*Generated from market research database | January 2026*
