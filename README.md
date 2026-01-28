# Phoenix Plumbing Market Competitor Analysis

Comprehensive competitive intelligence analysis for the Phoenix metropolitan area plumbing services market.

## Reports

| Report | Date | Competitors | Description |
|--------|------|-------------|-------------|
| [market-research-2026-01-28.md](./market-research-2026-01-28.md) | January 2026 | 122 | Full market analysis with per-competitor deep dives |

## Report Contents

### Executive Summary
- Market size and competitive landscape overview
- Key findings with statistical analysis
- Strategic recommendations

### Research Methodology
- Data collection methods (Google Places API, website crawling, PageSpeed Insights)
- Statistical framework using IQR-based outlier detection
- Limitations and data quality indicators

### Per-Competitor Analysis (122 competitors)
Each competitor section includes:
1. **Overview** - Website, rating, reviews, contact info
2. **Entity Classification** - Local Operator, Regional Brand, Enterprise Network, or Brand Aggregator
3. **Technology Stack** - CMS, analytics, chat widgets, booking systems
4. **Keyword Analysis** - Succeeding, wasteful, and missed keyword opportunities
5. **Content Analysis** - Page counts, word counts, content distribution
6. **Technical Performance** - Lighthouse scores, Core Web Vitals
7. **Page Load Times** - Response time percentiles
8. **Competitive Assessment** - Multi-dimensional power analysis with strengths/weaknesses

### Cross-Competitor Analysis
- Technology adoption trends
- Performance distribution
- Competitive clustering by entity class

## Data Sources

| Source | Coverage | Confidence |
|--------|----------|------------|
| Google Places API | 122 competitors | High |
| Website Crawl | 102 sites | High |
| PageSpeed Insights | 102 sites | High |
| Keyword Extraction | 95 sites | Medium |

## Key Findings

- **122 competitors** identified in Phoenix metro area
- **83%** have websites (102 of 122)
- **Median review count:** 108 reviews (IQR: 27-344)
- **20 statistical outliers** (review count > 814)
- **Average mobile score:** 61/100 (median: 60)
- **Average pages crawled:** 46 per site

## Geographic Scope

Phoenix metropolitan area with focus on west valley communities:
- Surprise
- Sun City / Sun City West
- Glendale (West)
- Peoria

ZIP codes: 85301-85388

## Methodology Notes

### Outlier Detection
Uses the Interquartile Range (IQR) method:
- Q1 = 27, Q3 = 344, IQR = 317
- Upper bound = 344 + (1.5 × 317) = 814
- Competitors with >814 reviews classified as statistical outliers

### Entity Classification
| Class | Criteria |
|-------|----------|
| Local Operator | Single location, <500 reviews |
| Regional Brand | 2-5 locations OR 500-2000 reviews |
| Enterprise Network | >5 locations OR >2000 reviews |
| Brand Aggregator | Multi-service (HVAC+Plumbing+Electrical) |

## License

This research data is provided for informational purposes. All data was collected from publicly available sources.

---

*Generated using [Plumber Market Research Platform](https://github.com/nestorwheelock/plumber)*
