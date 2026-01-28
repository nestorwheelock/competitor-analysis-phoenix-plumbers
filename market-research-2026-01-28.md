# Phoenix Plumbing Market Research Report
**[Versión en Español](./market-research-2026-01-28.es.md)** | English

## Comprehensive Competitive Intelligence Analysis | January 2026

**Report Generated:** 2026-01-28 20:32 UTC
**Geographic Focus:** Phoenix metropolitan area
**Analysis Tool:** Plumber Market Research Platform

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Research Methodology](#2-research-methodology)
3. [Market Overview](#3-market-overview)
4. [Statistical Framework](#4-statistical-framework)
5. [Competitor Analysis](#5-competitor-analysis) (122 competitors)
6. [Cross-Competitor Analysis](#6-cross-competitor-analysis)
7. [Appendices](#7-appendices)

---

## 1. Executive Summary

### 1.1 Research Objectives

This report provides comprehensive competitive intelligence for the Phoenix metropolitan area plumbing services market. The analysis aims to:

1. **Map the competitive landscape** - Identify and categorize all active competitors
2. **Assess digital presence** - Evaluate website quality, SEO performance, and technology adoption
3. **Identify opportunities** - Discover keyword gaps and competitive weaknesses
4. **Establish benchmarks** - Define market baselines for performance metrics

### 1.2 Key Findings

- **Market Size:** 122 competitors identified, 83% (102) have websites
- **Review Distribution:** Median 108 reviews (IQR: 27-344), 20 statistical outliers
- **Technical Performance:** Average mobile score 61 (median 60), 102 competitors analyzed
- **Content Depth:** 46 Average pages crawled per site

### 1.3 Strategic Recommendations

Based on the competitive analysis, the following strategic opportunities are identified:

1. **Technical Differentiation** - With a median mobile score of 60, achieving 80+ would place you in the top quartile
2. **Content Gap Exploitation** - Many competitors have thin content; comprehensive service pages represent an opportunity
3. **Keyword Targeting** - Focus on high-volume keywords with low competitive coverage
4. **Local SEO** - Geographic-specific pages for underserved zip codes

### 1.4 Data Quality Statement

This report is based on data collected from publicly available sources:

| Source | Coverage | Confidence |
|--------|----------|------------|
| Google Places API | 122/122 competitors | High |
| Website Crawl | 102/102 sites | High |
| PageSpeed Insights | 102/102 sites | High |
| Keyword Extraction | 95/102 sites | Medium |

**Note:** Review counts may be aggregated across multiple locations for enterprise competitors. See Section 4 for outlier treatment.

---

## 2. Research Methodology

### 2.1 Research Design

**Research Type:** Quantitative competitive intelligence analysis

**Geographic Scope:** Phoenix metropolitan area with focus on west valley communities
- Primary: Surprise, Sun City, Sun City West, Glendale (West), Peoria
- ZIP codes: 85301-85388 (23 unique codes)

**Temporal Scope:** Data collected January 2026

**Sample Size:** N = 122 competitors identified
- With websites: 102 (83.6%)
- With performance data: 102 (100.0% of websites)
- With keyword data: 95 (93.1% of websites)

### 2.2 Data Collection Methods

#### 2.2.1 Competitor Discovery

**Source:** Google Places API (Nearby Search)

**Method:**
1. Define search grid covering target ZIP codes
2. Query "plumber" + "plumbing" + related terms at each coordinate
3. Deduplicate by `place_id` (Google's unique identifier)
4. Enrich via Place Details API for complete business information

#### 2.2.2 Website Crawling

**Tool:** Custom Rust-based crawler

**Data Extracted Per Page:**
- URL, HTTP status code, response time (ms)
- Title tag, meta description, meta keywords
- H1 text, heading hierarchy (H1-H6)
- Word count (content text only)
- Internal/external link inventory

#### 2.2.3 Performance Analysis

**Source:** Google PageSpeed Insights API

**Metrics Collected:**
- Lighthouse scores (mobile, desktop): 0-100
- Core Web Vitals: LCP, INP, CLS
- Resource breakdown: HTML, CSS, JS, images, fonts

**Core Web Vitals Thresholds (per Google standards):**

| Metric | Good | Needs Improvement | Poor |
|--------|------|-------------------|------|
| LCP | ≤2.5s | ≤4.0s | >4.0s |
| INP | ≤200ms | ≤500ms | >500ms |
| CLS | ≤0.1 | ≤0.25 | >0.25 |

### 2.3 Data Quality & Limitations

**Known Limitations:**

1. **Discovery Bias** - Only businesses discoverable via Google Places API included
2. **Review Count Ambiguity** - Multi-location brands may have aggregated review counts
3. **Performance Snapshot** - PageSpeed scores captured at single point in time
4. **Keyword Extraction** - Based on crawled content only (not paid ads)

**Data Confidence Indicators:**

- **High** ✓ - Primary source verified, multiple signals corroborate
- **Medium** ~ - Single source, plausible but unverified
- **Low** ⚠ - Inferred, potential data quality issues
- **Unknown** ? - Data not collected or not applicable

---

## 3. Market Overview

### 3.1 Competitive Landscape Summary

| Metric | Value |
|--------|-------|
| Total Competitors Identified | 122 |
| With Active Websites | 102 |
| With Performance Data | 102 |
| With Keyword Data | 95 |

### 3.2 Review Distribution

| Statistic | Value |
|-----------|-------|
| Mean | 676 |
| Median | 108 |
| 25th Percentile (Q1) | 27 |
| 75th Percentile (Q3) | 344 |
| IQR | 317 |
| Outlier Threshold | >819 |

### 3.3 Technical Performance

| Metric | Value |
|--------|-------|
| Average Mobile Score | 61/100 |
| Median Mobile Score | 60/100 |
| Average Pages Crawled | 47 |

---

## 4. Statistical Framework

### 4.1 Outlier Detection (IQR Method)

For skewed distributions (e.g., review counts), we use the Interquartile Range method:

**Formula:**
```
Q1 = 25th percentile
Q3 = 75th percentile
IQR = Q3 - Q1
Upper bound = Q3 + 1.5 × IQR
```

**Application to Review Counts:**

- Q1 = 27, Q3 = 344, IQR = 317
- Upper bound = 344 + (1.5 × 317) = 819
- Competitors with >819 reviews classified as statistical outliers

### 4.2 Entity Classification Criteria

| Class | Criteria |
|-------|----------|
| Local Operator | Single location, <500 reviews |
| Regional Brand | 2-5 locations OR 500-2000 reviews |
| Enterprise Network | >5 locations OR >2000 reviews |
| Brand Aggregator | Multi-service (HVAC+Plumbing+Electrical) |

**Note:** Direct comparison between different entity classes may be misleading. This report clearly identifies entity class for context.

### 4.3 Performance Rating Thresholds

| Rating | Mobile Score | Description |
|--------|--------------|-------------|
| Excellent | 90-100 | Top-tier performance |
| Good | 80-89 | Above average |
| Needs Improvement | 50-79 | Average, has issues |
| Poor | 0-49 | Significant problems |

---

## 5. Competitor Analysis

This section provides detailed analysis for each of the 122 competitors identified.

### 100% Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.100percentplumber.com/ |
| Rating | 5.0/5 (1595 reviews) |
| Phone | (602) 757-6780 |
| Address | 17437 N 71st Dr Ste 106, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1595 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Housecall Pro, Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 15 | 3 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| review | 1776 | N/A |
| slider | 1400 | N/A |
| var | 1296 | N/A |
| water | 1234 | N/A |
| cur | 1120 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 90 | 47 | Above |
| Avg Word Count | 1206 | - | Good |
| Thin Content (<300) | 8 (8%) | - | Good |
| Rich Content (>1000) | 76 (84%) | - | Excellent |

**Content Distribution:**
- Service pages: 18
- Location pages: 0
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 51 | Needs Improvement |
| Desktop | 46 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 49.5s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 2 |
| Form Labels Missing | 7 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 7 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 97/100 | 1595 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 90 Pages |
| Technical | 48/100 | Mobile score 51 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (51) with 80+


---

### 24/7 Water Conditioning & Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.247plumbingaz.com/ |
| Rating | 4.4/5 (43 reviews) |
| Phone | (623) 206-4892 |
| Address | 18700 N 107th Ave #9B, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 43 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 27 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 99 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.7s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 54/100 | 43 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 99/100 | Mobile score 99 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### A Better Choice Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (9 reviews) |
| Phone | (602) 935-6501 |
| Address | 8542 W Tuckey Ln, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 9
- Standard local operator profile: 9 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 9 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### A to Z Prestigious Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://atozprestigious.com/ |
| Rating | 4.8/5 (35 reviews) |
| Phone | (602) 638-9911 |
| Address | 20064 W Luke Ave, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 35 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 5197 | N/A |
| specs | 4427 | N/A |
| false | 2381 | N/A |
| https | 2088 | N/A |
| com | 1812 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 14 | 47 | Below |
| Avg Word Count | 1480 | - | Good |
| Thin Content (<300) | 6 (42%) | - | Needs Work |
| Rich Content (>1000) | 8 (57%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 6
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 62 | Needs Improvement |
| Desktop | 90 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.9s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Mixed |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 58/100 | 35 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 14 Pages |
| Technical | 76/100 | Mobile score 62 |
| Brand | 35/100 | 1.8 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### A-1 Plumbing Contractors

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 3.0/5 (2 reviews) |
| Phone | (623) 915-5502 |
| Address | 5200 W Bethany Home Rd, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 2
- Standard local operator profile: 2 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 40/100 | 2 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### ALLPRO, by Denali

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.denalicorp.com/our-brands/appumping/ |
| Rating | 4.9/5 (39 reviews) |
| Phone | (623) 776-3230 |
| Address | 6525 W State Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 39 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Webflow markers found"],"name":"Webflow","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| color | 16571 | N/A |
| scheme | 14944 | N/A |
| var | 7418 | N/A |
| important | 6856 | N/A |
| 0rem | 5112 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 172 | 47 | Above |
| Avg Word Count | 1662 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 172 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 28
- Location pages: 19
- Blog posts: 3
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 60 | Needs Improvement |
| Desktop | 93 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 12.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 8 |
| Form Labels Missing | 10 |

**Issues:** Missing skip link, Missing lang attribute, 8 empty links, 10 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 59/100 | 39 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 172 Pages |
| Technical | 76/100 | Mobile score 60 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance, deep content

**Strengths:**
- Good technical performance
- Comprehensive content


---

### ATS Plumbing Inc.

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://atsplumbinginc.com/ |
| Rating | 5.0/5 (1 reviews) |
| Phone | (602) 690-7529 |
| Address | 7220 N Glen Harbor Blvd # 100, Glendale, AZ 85307, USA, Glendale, AZ, 85307 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Dormant Listing |
| Confidence | 70% |

**Evidence:**
- Very low review count: 1
- Domain age 1050 days with only 1 reviews

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| return | 447 | N/A |
| const | 368 | N/A |
| true | 352 | N/A |
| error | 333 | N/A |
| thunderbolt | 327 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 3176 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 2 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 70 | Needs Improvement |
| Desktop | 88 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 7.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Poor |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: Poor, Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 1 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 79/100 | Mobile score 70 |
| Brand | 50/100 | 2.9 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### AZ Home Services Group AC Repair & Plumbing Services of Sun City

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://azhomeservices.group/service-areas/sun-city-arizona-air-conditioner-plumbing-services/ |
| Rating | 5.0/5 (6 reviews) |
| Phone | (623) 307-5731 |
| Address | 10451 W Palmeras Dr, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 6
- Standard local operator profile: 6 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 61 | Needs Improvement |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.8s | ≤2.5s | Fail ✗ |
| CLS | 0.29 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 6 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 64/100 | Mobile score 61 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### AZ Pro Plumbing and Drain, LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.azproplumbinganddrain.com/ |
| Rating | 5.0/5 (11 reviews) |
| Phone | (602) 284-9208 |
| Address | 5635 W Villa Theresa Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 11 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| rtcommonprops | 282 | N/A |
| window | 270 | N/A |
| true | 202 | N/A |
| important | 196 | N/A |
| rtflags | 156 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 12 | 47 | Below |
| Avg Word Count | 2030 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 12 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 4
- Location pages: 2
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 91 | Excellent |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.7s | ≤2.5s | Needs Work |
| CLS | 0.07 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 11 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 12 Pages |
| Technical | 95/100 | Mobile score 91 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Ace Plumbers Phoenix AZ

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 4.9/5 (44 reviews) |
| Phone | (602) 603-4819 |
| Address | 10521 Cll De Las Casitas, Phoenix, AZ 85037, USA, Phoenix, AZ, 85037 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 44 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 59/100 | 44 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Adept Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://adeptplumbingllc.com/ |
| Rating | 5.0/5 (53 reviews) |
| Phone | (623) 692-8348 |
| Address | 2955 W Sandra Terrace, Phoenix, AZ 85053, USA, Phoenix, AZ, 85053 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 53 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (5 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 16 | N/A |
| plumbing | 14 | N/A |
| service | 12 | N/A |
| satisfaction | 10 | N/A |
| use | 10 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 6 | 47 | Below |
| Avg Word Count | 249 | - | Thin |
| Thin Content (<300) | 2 (33%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 76 | Needs Improvement |
| Desktop | 97 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.6s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 9 |
| Form Labels Missing | 1 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 9 empty links, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 53 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 6 Pages |
| Technical | 86/100 | Mobile score 76 |
| Brand | 75/100 | 6.5 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance, established brand; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Established brand presence

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### All Drains Emergency Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://alldrainsemergencyplumbing.com/ |
| Rating | 5.0/5 (186 reviews) |
| Phone | (602) 369-0958 |
| Address | 15826 N 64th Dr, Glendale, AZ 85306, USA, Glendale, AZ, 85306 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 186 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.7.4"}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 128419 | N/A |
| element | 78851 | N/A |
| wpr | 36451 | N/A |
| 0px | 22841 | N/A |
| color | 17639 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 103 | 47 | Above |
| Avg Word Count | 3022 | - | Good |
| Thin Content (<300) | 7 (6%) | - | Good |
| Rich Content (>1000) | 96 (93%) | - | Excellent |

**Content Distribution:**
- Service pages: 27
- Location pages: 44
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 47 | Poor |
| Desktop | 51 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 12.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 2 |
| Empty Links | 9 |
| Form Labels Missing | 3 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links, 3 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 186 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 103 Pages |
| Technical | 49/100 | Mobile score 47 |
| Brand | 50/100 | 2.8 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (47) with 80+


---

### All Hours Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://allhoursplumbingnow.com/ |
| Rating | 4.9/5 (65 reviews) |
| Phone | (602) 677-2615 |
| Address | 4741 W Park View Ln, Glendale, AZ 85310, USA, Glendale, AZ, 85310 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 65 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 761 | N/A |
| com | 541 | N/A |
| content | 510 | N/A |
| allhoursplumbingnow | 506 | N/A |
| https | 475 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 66 | 47 | Above |
| Avg Word Count | 686 | - | Average |
| Thin Content (<300) | 8 (12%) | - | Good |
| Rich Content (>1000) | 6 (9%) | - | Opportunity |

**Content Distribution:**
- Service pages: 8
- Location pages: 16
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 62 | Needs Improvement |
| Desktop | 78 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 20.2s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 6 |
| Empty Links | 4 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading, 4 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 65 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 66 Pages |
| Technical | 70/100 | Mobile score 62 |
| Brand | 35/100 | 1.7 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Alpha-Plumbing Services

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://alpha-plumbingservices.com/ |
| Rating | 5.0/5 (113 reviews) |
| Phone | (623) 734-7465 |
| Address | 16833 W Pierce St, Goodyear, AZ 85338, USA, Goodyear, AZ, 85338 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 113 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular | Medium |

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 4 | 47 | Below |
| Avg Word Count | 144 | - | Thin |
| Thin Content (<300) | 4 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 4
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 84 | Good |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.5s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 2 |
| Empty Links | 0 |
| Form Labels Missing | 1 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 113 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 4 Pages |
| Technical | 91/100 | Mobile score 84 |
| Brand | 50/100 | 2.7 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### American Home Water & Air

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://americanhomewater.com/ |
| Rating | 4.9/5 (2950 reviews) |
| Phone | (602) 975-2697 |
| Address | 2030 W Desert Cove Ave, Phoenix, AZ 85029, USA, Phoenix, AZ, 85029 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 2950 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 47737 | N/A |
| google | 32600 | N/A |
| element | 18703 | N/A |
| maps | 18192 | N/A |
| map | 17391 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4653 | - | Good |
| Thin Content (<300) | 53 (23%) | - | Needs Work |
| Rich Content (>1000) | 177 (76%) | - | Excellent |

**Content Distribution:**
- Service pages: 37
- Location pages: 64
- Blog posts: 1
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 35 | Poor |
| Desktop | 41 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 7.8s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 2950 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 38/100 | Mobile score 35 |
| Brand | 90/100 | 21.7 years |

**Threat Level: HIGH**

**Assessment:** Strong in strong reputation, deep content, established brand; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content
- Established brand presence

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (35) with 80+


---

### Amigo Rooter & Plumbing Phoenix Arizona

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.amigoplumbingaz.com/ |
| Rating | 4.8/5 (584 reviews) |
| Phone | (602) 446-6576 |
| Address | 3947 N 146th Dr, Goodyear, AZ 85395, USA, Goodyear, AZ, 85395 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 584 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | Housecall Pro, Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 1049 | N/A |
| space | 842 | N/A |
| water | 480 | N/A |
| class | 348 | N/A |
| rteblock | 348 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 10 | 47 | Below |
| Avg Word Count | 6733 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 10 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 35 | Poor |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 4 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 4 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 88/100 | 584 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 10 Pages |
| Technical | 57/100 | Mobile score 35 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Anthony's Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.dayandnightair.com/anthonysplumbing/?utm_source=Anthony%27s%20GMB%20redirect%20to%20DNT&utm_medium=Anthony%27s%20GMB&utm_campaign=redirect%20to%20DNT%20page |
| Rating | 4.8/5 (645 reviews) |
| Phone | (623) 936-5400 |
| Address | 1201 N 54th Ave #127, Phoenix, AZ 85043, USA, Phoenix, AZ, 85043 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 645 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 54 | Needs Improvement |
| Desktop | 63 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 88/100 | 645 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 58/100 | Mobile score 54 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Armstrong Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://armstrong-plumbing.com/?utm_source=google&utm_medium=GBP |
| Rating | 5.0/5 (284 reviews) |
| Phone | (602) 962-0888 |
| Address | 4420 W Creedance Blvd, Glendale, AZ 85310, USA, Glendale, AZ, 85310 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 284 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 98 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 100 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 0.8s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 284 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 100/100 | Mobile score 100 |
| Brand | 50/100 | 4.8 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Ascend Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.ascendplumbing.net/ |
| Rating | 4.8/5 (33 reviews) |
| Phone | (602) 946-4107 |
| Address | 100, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 33 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (5 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 37 | N/A |
| ascend | 22 | N/A |
| home | 19 | N/A |
| contact | 16 | N/A |
| calendar | 15 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 16 | 47 | Below |
| Avg Word Count | 87 | - | Thin |
| Thin Content (<300) | 16 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 69 | Needs Improvement |
| Desktop | 94 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 3 |
| Empty Links | 34 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, No H1 heading, 34 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 58/100 | 33 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 16 Pages |
| Technical | 81/100 | Mobile score 69 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### At your service plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 3.0/5 (4 reviews) |
| Phone | (623) 755-0104 |
| Address | 421 E Wigwam Blvd, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 4
- Standard local operator profile: 4 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 40/100 | 4 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Aurora Plumbing and Mechanical LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.auroraplumbingllc.net/ |
| Rating | 5.0/5 (56 reviews) |
| Phone | (623) 234-4496 |
| Address | 9577 W Ross Ave, Peoria, AZ 85382, USA, Peoria, AZ, 85382 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 56 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (11 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 30 | N/A |
| mechanical | 23 | N/A |
| usresidentialcommercial | 23 | N/A |
| auroraplumbingllc | 22 | N/A |
| industrialcareerscontact | 21 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 14 | 47 | Below |
| Avg Word Count | 219 | - | Thin |
| Thin Content (<300) | 12 (85%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 21.3s | ≤2.5s | Fail ✗ |
| CLS | 0.09 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 8 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 56 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 14 Pages |
| Technical | 62/100 | Mobile score 57 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation

**Strengths:**
- Strong review volume and ratings


---

### Authentic Plumbing, LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://authenticplumbingaz.com/ |
| Rating | 5.0/5 (255 reviews) |
| Phone | (602) 541-2361 |
| Address | 12220 W Candelaria Ct, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 255 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 71 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 18.2s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 255 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 63/100 | Mobile score 56 |
| Brand | 50/100 | 4.3 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Before & After Plumbing and Drain, LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.beforeandafterplumbing.com/?utm_source=GBP&utm_medium=organic&utm_campaign=gbp |
| Rating | 4.9/5 (960 reviews) |
| Phone | (623) 250-2584 |
| Address | 13059 W Grand Ave #9, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 960 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 3 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 3 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 52 | Needs Improvement |
| Desktop | 76 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.5s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 89/100 | 960 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 3 Pages |
| Technical | 64/100 | Mobile score 52 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Belsito Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.belsitoplumbing.com/ |
| Rating | 4.6/5 (280 reviews) |
| Phone | (480) 425-9900 |
| Address | 2215 W Melinda Ln # A, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 280 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 76/100 | 280 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Benjamin Franklin Plumbing of Phoenix, AZ

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.benfranklinplumbingaz.com/?utm_source=organic&utm_medium=gbp_listing |
| Rating | 4.8/5 (1893 reviews) |
| Phone | (480) 223-9348 |
| Address | 1911 W Parkside Ln, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1893 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 75 | Needs Improvement |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 13.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 13 | organic |

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 95/100 | 1893 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 87/100 | Mobile score 75 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Blackstone Plumbing Heating & Air Conditioning

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.blackstonehvacaz.com/ |
| Rating | 4.8/5 (157 reviews) |
| Phone | (602) 507-0222 |
| Address | 9915 W Bell Rd #448, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 157 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| hvac | 128 | N/A |
| services | 86 | N/A |
| document | 74 | N/A |
| service | 60 | N/A |
| installation | 54 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 16 | 47 | Below |
| Avg Word Count | 505 | - | Average |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 4
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 100 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.8s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 68/100 | 157 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 16 Pages |
| Technical | 100/100 | Mobile score 100 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Brothers Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 4.0/5 (1 reviews) |
| Phone | (623) 232-0731 |
| Address | 6730 W Frier Dr # 107, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 1
- Standard local operator profile: 1 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 50/100 | 1 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Bumble Bee Home Services

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://bumblebeeplumbingaz.com/?utm_source=google&utm_medium=organic&utm_campaign=GMBListing-glendale-az/ |
| Rating | 4.9/5 (3737 reviews) |
| Phone | (602) 813-0298 |
| Address | 7600 N 71st Ave, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 3737 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 131 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 82 | Good |
| Desktop | 98 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.9s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 3737 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 90/100 | Mobile score 82 |
| Brand | 90/100 | 13.7 years |

**Threat Level: HIGH**

**Assessment:** Strong in strong reputation, good technical performance, established brand; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Established brand presence

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Burnett's Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://burnettsplumbing.com/ |
| Rating | 5.0/5 (124 reviews) |
| Phone | (602) 472-1007 |
| Address | 32315 N 171st Ave, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 124 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Vue.js, Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (24 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| astro | 72 | N/A |
| let | 45 | N/A |
| getattribute | 39 | N/A |
| new | 39 | N/A |
| component | 33 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 6 | 47 | Below |
| Avg Word Count | 240 | - | Thin |
| Thin Content (<300) | 4 (66%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 72 | Needs Improvement |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 124 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 6 Pages |
| Technical | 85/100 | Mobile score 72 |
| Brand | 50/100 | 2.7 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Cactus Plumbing & Air

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://cactusplumbingandair.com/surprise-plumber-and-ac-repair/?utm_source=gmb&utm_medium=surprise |
| Rating | 4.9/5 (185 reviews) |
| Phone | (623) 294-2452 |
| Address | 12211 W Bell Rd Suite 109, Surprise, AZ 85378, USA, Surprise, AZ, 85378 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 185 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 17 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 15511 | N/A |
| function | 15128 | N/A |
| mejs | 14527 | N/A |
| repair | 14113 | N/A |
| plumber | 10667 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4067 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 44
- Location pages: 26
- Blog posts: 8
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 86 | Good |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.4s | ≤2.5s | Pass ✓ |
| CLS | 0.20 | ≤0.1 | Needs Work |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 185 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 92/100 | Mobile score 86 |
| Brand | 50/100 | 4.1 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: good technical performance, deep content

**Strengths:**
- Good technical performance
- Comprehensive content


---

### Cactus Plumbing And Air

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://cactusplumbingandair.com/sun-city-az/ |
| Rating | 4.9/5 (226 reviews) |
| Phone | (623) 294-8853 |
| Address | 12630 N 103rd Ave # 214, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 226 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 17 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 14667 | N/A |
| mejs | 14600 | N/A |
| plumbing | 14523 | N/A |
| repair | 14115 | N/A |
| plumber | 10992 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 3990 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 62
- Location pages: 9
- Blog posts: 30
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 92 | Excellent |
| Desktop | 97 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.7s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 226 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 94/100 | Mobile score 92 |
| Brand | 50/100 | 4.1 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content


---

### Cactus Plumbing And Air

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://cactusplumbingandair.com/glendale-plumber-and-ac-repair/?utm_source=gmb&utm_medium=glendale |
| Rating | 4.9/5 (185 reviews) |
| Phone | (623) 257-5117 |
| Address | 5008 W Glendale Ave Unit 105, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 185 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 17 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 15491 | N/A |
| function | 15128 | N/A |
| mejs | 14527 | N/A |
| repair | 14085 | N/A |
| plumber | 10617 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4064 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 43
- Location pages: 27
- Blog posts: 6
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | 88 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 185 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 69/100 | Mobile score N/A |
| Brand | 50/100 | 4.1 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: deep content

**Strengths:**
- Comprehensive content


---

### Canyon Plumbing Solutions

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://canyonplumbingsolutions.com/ |
| Rating | 5.0/5 (100 reviews) |
| Phone | (623) 335-9032 |
| Address | 2550 W Union Hills Dr #354, Phoenix, AZ 85023, USA, Phoenix, AZ, 85023 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 100 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Angular | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 9 | 2 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| color | 6242 | N/A |
| preset | 5148 | N/A |
| vivid | 3276 | N/A |
| var | 3068 | N/A |
| important | 2705 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 85 | 47 | Above |
| Avg Word Count | 1359 | - | Good |
| Thin Content (<300) | 6 (7%) | - | Good |
| Rich Content (>1000) | 67 (78%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 20
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 67 | Needs Improvement |
| Desktop | 82 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 14.7s | ≤2.5s | Fail ✗ |
| CLS | 0.04 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 2 |
| Empty Links | 1 |
| Form Labels Missing | 2 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 100 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 85 Pages |
| Technical | 74/100 | Mobile score 67 |
| Brand | 20/100 | 0.9 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### Canyon State Service Experts

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.serviceexperts.com/surprise-az?&utm_campaign=listing&utm_medium=organic_search&utm_source=gmb&utm_content=brand |
| Rating | 4.9/5 (2444 reviews) |
| Phone | (602) 844-4104 |
| Address | 11560 N Dysart Rd Suite 116, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 2444 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | ServiceTitan | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 14 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| service | 8130 | N/A |
| experts | 5959 | N/A |
| services | 5469 | N/A |
| var | 3800 | N/A |
| process | 3588 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2347 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 194 (84%) | - | Excellent |

**Content Distribution:**
- Service pages: 230
- Location pages: 33
- Blog posts: 17
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 63 | Needs Improvement |
| Desktop | 60 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.7s | ≤2.5s | Needs Work |
| CLS | 0.09 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 13 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 2444 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 61/100 | Mobile score 63 |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content

**Strengths:**
- Strong review volume and ratings
- Comprehensive content


---

### Christian Brothers Plumbing, A/C, & Electrical

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://cbrothers.com/?utm_source=google&utm_medium=organic&utm_campaign=gbp |
| Rating | 4.8/5 (2105 reviews) |
| Phone | (623) 939-9421 |
| Address | 6827 W Belmont Ave, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 2105 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 95 | 36 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| repair | 4122 | N/A |
| electrical | 3229 | N/A |
| plumbing | 2992 | N/A |
| air | 2836 | N/A |
| water | 2811 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1263 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 198 (86%) | - | Excellent |

**Content Distribution:**
- Service pages: 18
- Location pages: 67
- Blog posts: 1
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 71 | Needs Improvement |
| Desktop | 78 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.3s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 5 |
| Form Labels Missing | 8 |

**Issues:** Missing skip link, Missing lang attribute, 5 empty links, 8 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 95/100 | 2105 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 74/100 | Mobile score 71 |
| Brand | 90/100 | 23.9 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content
- Established brand presence


---

### Copper State Plumbing Services LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 3.9/5 (22 reviews) |
| Phone | (602) 561-3391 |
| Address | 13444 W Ocotillo Ln, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 22 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 49/100 | 22 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Courtesy Plumbing of AZ, LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://courtesyplumbingofaz.com/ |
| Rating | 4.6/5 (42 reviews) |
| Phone | (623) 247-7952 |
| Address | 6014 W Glendale Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 42 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 88 | N/A |
| roc | 88 | N/A |
| use | 45 | N/A |
| bonded | 44 | N/A |
| insured | 44 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 23 | 47 | Below |
| Avg Word Count | 231 | - | Thin |
| Thin Content (<300) | 20 (86%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 66 | Needs Improvement |
| Desktop | 82 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.6s | ≤2.5s | Fail ✗ |
| CLS | 0.15 | ≤0.1 | Needs Work |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 56/100 | 42 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 23 Pages |
| Technical | 74/100 | Mobile score 66 |
| Brand | 35/100 | 1.1 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Darrels drain cleaning & locating

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.phxdraincleaning.com/ |
| Rating | 4.4/5 (41 reviews) |
| Phone | (602) 402-3727 |
| Address | 10909 W Camelot Cir, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 41 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 93 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 99 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 2.2s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 54/100 | 41 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 99/100 | Mobile score 99 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Deer Valley Plumbing & Air Conditioning

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.deervalleyplumbing.com/?utm_source=GMB&utm_medium=organic&utm_campaign=glendale |
| Rating | 5.0/5 (41 reviews) |
| Phone | (623) 283-4500 |
| Address | 9524 W Camelback Rd STE 130-440, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 41 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 34 | Poor |
| Desktop | 62 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.0s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 41 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 48/100 | Mobile score 34 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: poor technical performance, thin content

**Weaknesses:**
- Poor mobile performance
- Thin content

**Opportunities to Exploit:**
- Beat their mobile score (34) with 80+
- Create deeper content than their thin pages


---

### Deer Valley Plumbing & Air Conditioning

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.deervalleyplumbing.com/ |
| Rating | 4.8/5 (1237 reviews) |
| Phone | (623) 281-3783 |
| Address | 2411 W Lone Cactus Dr, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1237 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 36 | Poor |
| Desktop | 78 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.0s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 0 |
| Avg Position | 10.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 10 | organic |

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 95/100 | 1237 reviews |
| SERP | 3/100 | 1 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 57/100 | Mobile score 36 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Desert Water Plumbing and Rooter

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.desertwateraz.com/near-me-plumber-peoria-az/?utm_source=google&utm_medium=organic&utm_campaign=gbp_peoria |
| Rating | 5.0/5 (924 reviews) |
| Phone | (602) 641-2998 |
| Address | 8301 W Foothill Dr, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 924 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 325 | N/A |
| function | 253 | N/A |
| true | 200 | N/A |
| plumbing | 185 | N/A |
| repair | 183 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 70 | 47 | Above |
| Avg Word Count | 244 | - | Thin |
| Thin Content (<300) | 64 (91%) | - | Needs Work |
| Rich Content (>1000) | 6 (8%) | - | Opportunity |

**Content Distribution:**
- Service pages: 6
- Location pages: 8
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 72 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.1s | ≤2.5s | Needs Work |
| CLS | 0.32 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 0 |
| Form Labels Missing | 2 |

**Issues:** Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 90/100 | 924 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 70 Pages |
| Technical | 75/100 | Mobile score 72 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### Dh Plumbing Llc

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 4.8/5 (67 reviews) |
| Phone | (623) 220-1800 |
| Address | 6626 W Villa Theresa Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 67 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 68/100 | 67 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Diamondback Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.diamondbackplumbing.com/ |
| Rating | 4.5/5 (690 reviews) |
| Phone | (602) 428-0910 |
| Address | 17423 N 25th Ave, Phoenix, AZ 85023, USA, Phoenix, AZ, 85023 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 690 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| width | 2044 | N/A |
| height | 1306 | N/A |
| min | 1244 | N/A |
| padding | 1149 | N/A |
| flex | 991 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 34 | 47 | Below |
| Avg Word Count | 2784 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 34 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 77 | Needs Improvement |
| Desktop | 99 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.8s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 34.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 34 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 11 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 85/100 | 690 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 40/100 | 34 Pages |
| Technical | 88/100 | Mobile score 77 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### Dignity Plumbers Service & Water Softeners

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.dignityplumbingaz.com/ |
| Rating | 5.0/5 (813 reviews) |
| Phone | (623) 235-4045 |
| Address | 11200 W Wisconsin Ave #5A, Youngtown, AZ 85363, USA, Youngtown, AZ, 85363 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 813 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 2 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 42 | Poor |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.7s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 90/100 | 813 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 46/100 | Mobile score 42 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in poor technical performance, thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Poor mobile performance
- Thin content

**Opportunities to Exploit:**
- Beat their mobile score (42) with 80+
- Create deeper content than their thin pages


---

### Donley A/C & Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.donleyservice.com/ |
| Rating | 4.9/5 (1119 reviews) |
| Phone | (480) 295-7385 |
| Address | 11062 N 24th Ave, Phoenix, AZ 85029, USA, Phoenix, AZ, 85029 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1119 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | ServiceTitan | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 24 | 2 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 10761 | N/A |
| hvac | 7576 | N/A |
| sewer | 6388 | N/A |
| water | 5191 | N/A |
| drains | 5075 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2157 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 230
- Location pages: 80
- Blog posts: 74
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 74 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.0s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 13 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 1119 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 76/100 | Mobile score 74 |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content


---

### Drain Squad A Plumbing & Drain

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.drainsquadplumbing.com/ |
| Rating | 4.5/5 (42 reviews) |
| Phone | (623) 594-4333 |
| Address | 4446 N 126th Dr, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 42 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 641 | N/A |
| drain | 301 | N/A |
| function | 301 | N/A |
| source | 253 | N/A |
| plumbing | 242 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 27 | 47 | Below |
| Avg Word Count | 1673 | - | Good |
| Thin Content (<300) | 2 (7%) | - | Good |
| Rich Content (>1000) | 25 (92%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 26 | Poor |
| Desktop | 38 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.0s | ≤2.5s | Fail ✗ |
| CLS | 1.00 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 9 |
| Form Labels Missing | 21 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links, 21 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 55/100 | 42 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 27 Pages |
| Technical | 32/100 | Mobile score 26 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: poor technical performance

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (26) with 80+


---

### Drain Tech Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://fast-plumbing-glendale.com/ |
| Rating | 5.0/5 (14 reviews) |
| Phone | (408) 705-2633 |
| Address | 5901 W Behrend Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 14 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 94 | Excellent |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.7s | ≤2.5s | Pass ✓ |
| CLS | 0.15 | ≤0.1 | Needs Work |

**Improvement Opportunities:**
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 14 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 97/100 | Mobile score 94 |
| Brand | 50/100 | 3.0 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### E.R. Tankless & Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://erplumbingaz.com/ |
| Rating | 5.0/5 (82 reviews) |
| Phone | (480) 262-8662 |
| Address | 25904 N 96th Ln, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 82 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | jQuery | Medium |

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 3265 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 2 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 59 | Needs Improvement |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.6s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 82 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 57/100 | Mobile score 59 |
| Brand | 75/100 | 5.5 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, established brand; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Established brand presence

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Echo Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://echoplumbingaz.com/ |
| Rating | 5.0/5 (76 reviews) |
| Phone | (602) 515-5171 |
| Address | 17646 W Running Deer Trl, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 76 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Vue.js, Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| document | 173 | N/A |
| function | 107 | N/A |
| var | 93 | N/A |
| style | 65 | N/A |
| addeventlistener | 44 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 34 | 47 | Below |
| Avg Word Count | 125 | - | Thin |
| Thin Content (<300) | 32 (94%) | - | Needs Work |
| Rich Content (>1000) | 2 (5%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 2
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 62 | Needs Improvement |
| Desktop | 83 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 28.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 15 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 15 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 76 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 34 Pages |
| Technical | 72/100 | Mobile score 62 |
| Brand | 35/100 | 1.6 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### Edge Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://edgeplumbingllc.com/ |
| Rating | 5.0/5 (29 reviews) |
| Phone | (623) 208-1668 |
| Address | 13337 W Cottonwood St, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 29 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.8.3"}  | Medium |
| Booking | Housecall Pro | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 2271 | N/A |
| plumbing | 2198 | N/A |
| window | 1906 | N/A |
| elem | 1508 | N/A |
| style | 1419 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 154 | 47 | Above |
| Avg Word Count | 945 | - | Good |
| Thin Content (<300) | 16 (10%) | - | Good |
| Rich Content (>1000) | 60 (38%) | - | Excellent |

**Content Distribution:**
- Service pages: 19
- Location pages: 47
- Blog posts: 6
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 39 | Poor |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 27.7s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 29 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 154 Pages |
| Technical | 47/100 | Mobile score 39 |
| Brand | 20/100 | 1.0 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in deep content; vulnerable in poor technical performance

**Strengths:**
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (39) with 80+


---

### Emergency Master Plumbing & Air

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://emergencymasterplumbingair.com/ |
| Rating | 4.9/5 (727 reviews) |
| Phone | (623) 584-4706 |
| Address | 16200 N 154th Dr, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 727 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 1 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| block | 910 | N/A |
| emergencymasterplumbingair | 873 | N/A |
| com | 872 | N/A |
| https | 541 | N/A |
| content | 508 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 398 | 47 | Above |
| Avg Word Count | 102 | - | Thin |
| Thin Content (<300) | 395 (99%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 40
- Location pages: 175
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 66 | Needs Improvement |
| Desktop | 81 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 89/100 | 727 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 398 Pages |
| Technical | 73/100 | Mobile score 66 |
| Brand | 50/100 | 3.7 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content


---

### Emergency Plumbing Hero

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.yourplumbinghero.com/ |
| Rating | 5.0/5 (41 reviews) |
| Phone | (602) 301-1664 |
| Address | 6737 W Glendale Ave, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 41 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 11784 | N/A |
| div | 5600 | N/A |
| element | 5554 | N/A |
| data | 4880 | N/A |
| classname | 4560 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2120 | - | Good |
| Thin Content (<300) | 19 (8%) | - | Good |
| Rich Content (>1000) | 167 (72%) | - | Excellent |

**Content Distribution:**
- Service pages: 78
- Location pages: 17
- Blog posts: 91
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 9 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 41 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: deep content

**Strengths:**
- Comprehensive content


---

### Faucet Doctor Plumbing and HVAC Services

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.faucetdoctorplumbingaz.com/ |
| Rating | 4.9/5 (1110 reviews) |
| Phone | (623) 214-7161 |
| Address | 28214 N 168th Ave, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1110 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| blurb | 4205 | N/A |
| header | 4082 | N/A |
| footer | 3871 | N/A |
| important | 3402 | N/A |
| menu | 3388 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 63 | 47 | Above |
| Avg Word Count | 1107 | - | Good |
| Thin Content (<300) | 9 (14%) | - | Good |
| Rich Content (>1000) | 36 (57%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 4
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 51 | Needs Improvement |
| Desktop | 37 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.9s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 1110 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 63 Pages |
| Technical | 44/100 | Mobile score 51 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (51) with 80+


---

### Flow Tech Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.flowtechplumbingaz.com/general-plumbing |
| Rating | 5.0/5 (341 reviews) |
| Phone | (623) 303-7736 |
| Address | 10530 W Sands Dr, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 341 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Booking | Housecall Pro, Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| block | 21168 | N/A |
| sqs | 10821 | N/A |
| width | 7678 | N/A |
| yui | 6575 | N/A |
| grid | 6052 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 164 | 47 | Above |
| Avg Word Count | 2445 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 164 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 103
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 36 | Poor |
| Desktop | 45 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.6s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 341 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 164 Pages |
| Technical | 40/100 | Mobile score 36 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (36) with 80+


---

### Flush King Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://flushking.com/ |
| Rating | 4.8/5 (468 reviews) |
| Phone | (602) 644-1950 |
| Address | 6619 N Scottsdale Rd, Scottsdale, AZ 85250, USA, Scottsdale, AZ, 85250 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 468 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.8.3"}  | Medium |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 5281 | N/A |
| fusion | 5163 | N/A |
| header | 4499 | N/A |
| plumbing | 4286 | N/A |
| cdata | 3909 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1081 | - | Good |
| Thin Content (<300) | 7 (3%) | - | Good |
| Rich Content (>1000) | 200 (86%) | - | Excellent |

**Content Distribution:**
- Service pages: 26
- Location pages: 170
- Blog posts: 7
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | 93 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 78/100 | 468 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 71/100 | Mobile score N/A |
| Brand | 90/100 | 26.3 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content
- Established brand presence


---

### Forrest Anderson Plumbing & Air Conditioning

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://forrestanderson.net/ |
| Rating | 4.6/5 (108 reviews) |
| Phone | (623) 780-4060 |
| Address | 17225 N 63rd Ave, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 108 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 509360 | N/A |
| specs | 462717 | N/A |
| false | 206007 | N/A |
| https | 143427 | N/A |
| com | 117862 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4163 | - | Good |
| Thin Content (<300) | 4 (1%) | - | Good |
| Rich Content (>1000) | 224 (97%) | - | Excellent |

**Content Distribution:**
- Service pages: 3
- Location pages: 37
- Blog posts: 8
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 52 | Needs Improvement |
| Desktop | 75 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.5s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Mixed |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 11 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading, 11 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 66/100 | 108 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 63/100 | Mobile score 52 |
| Brand | 90/100 | 21.2 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: deep content, established brand

**Strengths:**
- Comprehensive content
- Established brand presence


---

### Glendale Plumbing Experts

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (24 reviews) |
| Phone | (520) 392-7887 |
| Address | 6631 W Peoria Ave, Glendale, AZ 85302, USA, Glendale, AZ, 85302 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 24 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 24 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Good Guys Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.good-guys-plumbing.com/ |
| Rating | 5.0/5 (6 reviews) |
| Phone | (623) 776-2457 |
| Address | 8427 W Glendale Ave Lot 55, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 6
- Standard local operator profile: 6 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 1049 | N/A |
| good | 984 | N/A |
| guys | 983 | N/A |
| var | 915 | N/A |
| supports | 912 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 108 | 47 | Above |
| Avg Word Count | 433 | - | Average |
| Thin Content (<300) | 4 (3%) | - | Good |
| Rich Content (>1000) | 6 (5%) | - | Opportunity |

**Content Distribution:**
- Service pages: 14
- Location pages: 52
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.6s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 6 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 108 Pages |
| Technical | 67/100 | Mobile score 56 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: deep content

**Strengths:**
- Comprehensive content


---

### Grand Canyon Home Services

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://grandcanyonac.com/surprise-az/?utm_source=gmb&utm_medium=organic&utm_campaign=suprise |
| Rating | 4.9/5 (331 reviews) |
| Phone | (623) 444-6988 |
| Address | 15331 W Bell Rd Ste. 212-66, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 331 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 10073 | N/A |
| services | 6663 | N/A |
| var | 5845 | N/A |
| return | 5425 | N/A |
| document | 5209 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 171 | 47 | Above |
| Avg Word Count | 2894 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 171 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 17
- Location pages: 51
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 53 | Needs Improvement |
| Desktop | 64 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 13.7s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 6 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 6 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 331 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 171 Pages |
| Technical | 58/100 | Mobile score 53 |
| Brand | 90/100 | 14.8 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Comprehensive content
- Established brand presence


---

### Hotrod plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.hotrod-plumbing.com/ |
| Rating | 5.0/5 (159 reviews) |
| Phone | (480) 210-9957 |
| Address | 2920 W Robin Ln, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 159 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Vue.js, Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (23 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 60 | N/A |
| hotrod | 36 | N/A |
| content | 31 | N/A |
| com | 30 | N/A |
| https | 28 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 38 | 47 | Average |
| Avg Word Count | 1716 | - | Good |
| Thin Content (<300) | 2 (5%) | - | Good |
| Rich Content (>1000) | 26 (68%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 75 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 18.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 16 |
| Form Labels Missing | 1 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 16 empty links, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 159 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 38 Pages |
| Technical | 65/100 | Mobile score 56 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation

**Strengths:**
- Strong review volume and ratings


---

### Impact Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (53 reviews) |
| Phone | (623) 330-0858 |
| Address | 11828 N 44th Ave, Glendale, AZ 85304, USA, Glendale, AZ, 85304 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 53 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 53 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Instant Plumbing and Rooter

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://instant.plumbing/?utm_source=organic&utm_medium=gbp&utm_campaign=testing&utm_id=9x10&utm_term=post |
| Rating | 5.0/5 (344 reviews) |
| Phone | (480) 353-7267 |
| Address | 4340 W Charleston Ave, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 344 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 97 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 63 | Needs Improvement |
| Desktop | 77 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 344 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 70/100 | Mobile score 63 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### JV7 Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://jv7plumbingllc.com/ |
| Rating | 5.0/5 (21 reviews) |
| Phone | (602) 621-7894 |
| Address | 7502 N 47th Dr A14, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 21 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| mejs | 7957 | N/A |
| jacqueline | 5341 | N/A |
| storage | 5341 | N/A |
| empty | 2616 | N/A |
| error | 2442 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 179 | 47 | Above |
| Avg Word Count | 899 | - | Good |
| Thin Content (<300) | 43 (24%) | - | Needs Work |
| Rich Content (>1000) | 111 (62%) | - | Excellent |

**Content Distribution:**
- Service pages: 11
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 40 | Poor |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.8s | ≤2.5s | Fail ✗ |
| CLS | 0.34 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 3 |
| Empty Links | 5 |
| Form Labels Missing | 4 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading, 5 empty links, 4 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 21 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 179 Pages |
| Technical | 59/100 | Mobile score 40 |
| Brand | 75/100 | 7.4 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: deep content, established brand

**Strengths:**
- Comprehensive content
- Established brand presence


---

### Kay's Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (52 reviews) |
| Phone | (623) 824-3975 |
| Address | 19808 N 44th Dr, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 52 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 52 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### King Charles Plumbing & Air Conditioning

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://kingcharles.com/?utm_source=gmb&utm_medium=surprise |
| Rating | 5.0/5 (630 reviews) |
| Phone | (623) 223-8065 |
| Address | 14924 W Lamoille Dr, Surprise, AZ 85374, USA, Surprise, AZ, 85374 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 80% |

**Evidence:**
- Regional review count: 630 (range: 500-2000)
- Established domain: 26 years

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| https | 78 | N/A |
| com | 75 | N/A |
| water | 70 | N/A |
| kingcharles | 69 | N/A |
| content | 67 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 71 | 47 | Above |
| Avg Word Count | 108 | - | Thin |
| Thin Content (<300) | 68 (95%) | - | Needs Work |
| Rich Content (>1000) | 3 (4%) | - | Opportunity |

**Content Distribution:**
- Service pages: 6
- Location pages: 7
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 88 | Good |
| Desktop | 100 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.8s | ≤2.5s | Needs Work |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 90/100 | 630 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 71 Pages |
| Technical | 94/100 | Mobile score 88 |
| Brand | 90/100 | 26.2 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, established brand

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Established brand presence


---

### Lawson Family Plumbing Inc.

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://lawsonfamilyplumbing.com/ |
| Rating | 4.8/5 (1541 reviews) |
| Phone | (602) 413-5790 |
| Address | 1497 E Baseline Rd STE 110, Gilbert, AZ 85233, USA, Gilbert, AZ, 85233 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 80% |

**Evidence:**
- Regional review count: 1541 (range: 500-2000)
- Established domain: 14 years

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| com | 582 | N/A |
| lawsonfamilyplumbing | 582 | N/A |
| https | 532 | N/A |
| content | 482 | N/A |
| png | 482 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 83 | 47 | Above |
| Avg Word Count | 104 | - | Thin |
| Thin Content (<300) | 81 (97%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 12
- Location pages: 5
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 49 | Poor |
| Desktop | 72 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 95/100 | 1541 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 83 Pages |
| Technical | 60/100 | Mobile score 49 |
| Brand | 90/100 | 14.8 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, established brand

**Strengths:**
- Strong review volume and ratings
- Established brand presence


---

### Leak Hunters: Leak Detection

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.leakhuntersaz.com/ |
| Rating | 4.9/5 (129 reviews) |
| Phone | (623) 980-2888 |
| Address | 8379 W Midway Ave, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 129 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| leak | 235 | N/A |
| const | 152 | N/A |
| detection | 139 | N/A |
| water | 125 | N/A |
| pool | 82 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 39 | 47 | Average |
| Avg Word Count | 272 | - | Thin |
| Thin Content (<300) | 27 (69%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 10
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 85 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 129 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 39 Pages |
| Technical | 71/100 | Mobile score 57 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Lee's Air, Plumbing, & Heating

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://leesair.com/peoria/ |
| Rating | 5.0/5 (94 reviews) |
| Phone | (602) 649-2180 |
| Address | 9210 W Peoria Ave Suite 6b, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 94 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | ServiceTitan, Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 84 | 4 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| elementor | 25620 | N/A |
| color | 25415 | N/A |
| var | 13364 | N/A |
| preset | 11583 | N/A |
| element | 10466 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 3033 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 44
- Location pages: 107
- Blog posts: 3
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 45 | Poor |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 11.0s | ≤2.5s | Fail ✗ |
| CLS | 0.07 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 3 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 94 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 56/100 | Mobile score 45 |
| Brand | 90/100 | 25.4 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Comprehensive content
- Established brand presence


---

### Lucky Duck Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 4.8/5 (57 reviews) |
| Phone | (623) 341-3245 |
| Address | 10135 W Denton Ln, Glendale, AZ 85307, USA, Glendale, AZ, 85307 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 57 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 68/100 | 57 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Maloney Plumbing & Drain Services in Phoenix, AZ

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.maloneyplumbing.com/?utm_source=gmb&utm_medium=organic |
| Rating | 4.9/5 (1025 reviews) |
| Phone | (602) 671-3617 |
| Address | 9119 7th St Suite 201, Phoenix, AZ 85020, USA, Phoenix, AZ, 85020 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1025 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 46 | Poor |
| Desktop | 80 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 26.6s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 41.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 41 | organic |

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 1025 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 63/100 | Mobile score 46 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Navarro Plumbing Services LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 4.4/5 (23 reviews) |
| Phone | (602) 750-5551 |
| Address | 5526 N 84th Ln, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 23 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 54/100 | 23 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### One Shot Installation Electrical, Plumbing & Appliance Repair-Electrician & Plumber Phoenix, AZ.

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.oneshotinstallation.com/ |
| Rating | 4.9/5 (176 reviews) |
| Phone | (602) 791-5659 |
| Address | 12370 N 83rd Ave, Peoria, AZ 85381, USA, Peoria, AZ, 85381 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 176 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (23 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 24 | N/A |
| testimony | 22 | N/A |
| service | 20 | N/A |
| electrician | 16 | N/A |
| flagstaff | 16 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 10 | 47 | Below |
| Avg Word Count | 419 | - | Average |
| Thin Content (<300) | 6 (60%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 68 | Needs Improvement |
| Desktop | 86 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.8s | ≤2.5s | Needs Work |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 176 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 10 Pages |
| Technical | 77/100 | Mobile score 68 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### P3 Plumbing AZ

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://p3plumbingaz.com/ |
| Rating | 5.0/5 (216 reviews) |
| Phone | (623) 271-2941 |
| Address | 29516 N 223rd Dr, Wittmann, AZ 85361, USA, Wittmann, AZ, 85361 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 216 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Vue.js, Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| menu | 10520 | N/A |
| item | 8989 | N/A |
| class | 4559 | N/A |
| https | 4202 | N/A |
| com | 4114 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 94 | 47 | Above |
| Avg Word Count | 947 | - | Good |
| Thin Content (<300) | 36 (38%) | - | Needs Work |
| Rich Content (>1000) | 53 (56%) | - | Excellent |

**Content Distribution:**
- Service pages: 1
- Location pages: 20
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 64 | Needs Improvement |
| Desktop | 91 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.7s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 11 |
| Empty Links | 0 |
| Form Labels Missing | 5 |

**Issues:** Missing skip link, Missing lang attribute, 5 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 216 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 94 Pages |
| Technical | 77/100 | Mobile score 64 |
| Brand | 20/100 | 0.9 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### POP Plumbing LLC - Glendale

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://popplumbing.co/ |
| Rating | 5.0/5 (155 reviews) |
| Phone | (602) 529-0025 |
| Address | 8355 W Midway Ave, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 155 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Vue.js, Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| astro | 96 | N/A |
| let | 60 | N/A |
| getattribute | 52 | N/A |
| new | 52 | N/A |
| component | 44 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 8 | 47 | Below |
| Avg Word Count | 252 | - | Thin |
| Thin Content (<300) | 8 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 67 | Needs Improvement |
| Desktop | 95 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.0s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 9 |
| Form Labels Missing | 3 |

**Issues:** Missing skip link, Missing lang attribute, 9 empty links, 3 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 155 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 8 Pages |
| Technical | 81/100 | Mobile score 67 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Parker & Sons

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.parkerandsons.com/?utm_campaign=gmb_pk-phx_home_cus-all_googlebusinessprofile&utm_medium=gmb&utm_source=google |
| Rating | 4.7/5 (31728 reviews) |
| Phone | (602) 424-9619 |
| Address | 3636 E Anne St A, Phoenix, AZ 85040, USA, Phoenix, AZ, 85040 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 31728 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | ServiceTitan | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| window | 16698 | N/A |
| digitaldata | 10600 | N/A |
| var | 9114 | N/A |
| dlobj | 8600 | N/A |
| digitallaunchdata | 8400 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 4127 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 230 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 6
- Location pages: 7
- Blog posts: 140
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 44 | Poor |
| Desktop | 45 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 26.2s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 1 |
| Avg Position | 1.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 1 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 94/100 | 31728 reviews |
| SERP | 3/100 | 1 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 44/100 | Mobile score 44 |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (44) with 80+


---

### Patriotic Plumbing And Rooter

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://patrioticplumbingandrooter.com/ |
| Rating | 4.9/5 (293 reviews) |
| Phone | (602) 755-9373 |
| Address | 14208 N 138th Dr, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 293 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Housecall Pro, ScheduleOnce, Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| rpi | 53352 | N/A |
| var | 45096 | N/A |
| color | 31191 | N/A |
| important | 27079 | N/A |
| background | 16524 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 182 | 47 | Above |
| Avg Word Count | 4430 | - | Good |
| Thin Content (<300) | 6 (3%) | - | Good |
| Rich Content (>1000) | 176 (96%) | - | Excellent |

**Content Distribution:**
- Service pages: 53
- Location pages: 80
- Blog posts: 77
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 83 | Good |
| Desktop | 69 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.1s | ≤2.5s | Needs Work |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 13 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 13 empty links, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 293 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 182 Pages |
| Technical | 76/100 | Mobile score 83 |
| Brand | 75/100 | 5.5 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content
- Established brand presence


---

### Peoria Plumbing & Drain Experts

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://peoriaplumbingdrainexperts.site/ |
| Rating | 5.0/5 (22 reviews) |
| Phone | (623) 283-4574 |
| Address | 9772 N Lake Pleasant Pkwy, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 22 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 22 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | 0.2 years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Phay Plumbing services LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://phayplumbingaz.com/ |
| Rating | 5.0/5 (253 reviews) |
| Phone | (602) 291-0525 |
| Address | 15941 W Madison St, Goodyear, AZ 85338, USA, Goodyear, AZ, 85338 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 253 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 2 | 2 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| photos | 17480 | N/A |
| checkin | 15470 | N/A |
| https | 11979 | N/A |
| com | 11111 | N/A |
| plumbing | 10915 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 97 | 47 | Above |
| Avg Word Count | 6890 | - | Good |
| Thin Content (<300) | 8 (8%) | - | Good |
| Rich Content (>1000) | 89 (91%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 28
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 63 | Needs Improvement |
| Desktop | 83 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 11.3s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 0 |
| Form Labels Missing | 7 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 7 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 253 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 97 Pages |
| Technical | 73/100 | Mobile score 63 |
| Brand | 50/100 | 2.9 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### Phoenician Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.phoenicianplumbing.com/?utm_source=google&utm_medium=wix_google_business_profile&utm_campaign=16294771040885588611 |
| Rating | 4.8/5 (25 reviews) |
| Phone | (623) 290-3272 |
| Address | 9007 W Malapai Dr, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 25 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 58/100 | 25 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Phoenix Pipe Bursting

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://phoenixpipebursting.com/?utm_source=local&utm_medium=organic&utm_campaign=gbp |
| Rating | 5.0/5 (4 reviews) |
| Phone | (602) 900-9050 |
| Address | 8550 N 91st Ave #83, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 4
- Standard local operator profile: 4 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Housecall Pro | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| color | 660 | N/A |
| important | 511 | N/A |
| preset | 495 | N/A |
| var | 486 | N/A |
| vivid | 315 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 10 | 47 | Below |
| Avg Word Count | 3627 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 10 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 10
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 80 | Good |
| Desktop | 98 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.6s | ≤2.5s | Needs Work |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 4 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 10 Pages |
| Technical | 89/100 | Mobile score 80 |
| Brand | 20/100 | 0.4 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Pink Plumbing and Sewer

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.pinkplumbingandsewer.com/ |
| Rating | 4.9/5 (189 reviews) |
| Phone | (602) 562-5290 |
| Address | 2375 E Camelback Rd #600, Phoenix, AZ 85016, USA, Phoenix, AZ, 85016 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 189 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| com | 221 | N/A |
| https | 221 | N/A |
| plumbing | 220 | N/A |
| pinkplumbingandsewer | 219 | N/A |
| sewer | 192 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 48 | 47 | Average |
| Avg Word Count | 633 | - | Average |
| Thin Content (<300) | 10 (20%) | - | Needs Work |
| Rich Content (>1000) | 6 (12%) | - | Good |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 79 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.1s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 15.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 15 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 189 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 40/100 | 48 Pages |
| Technical | 68/100 | Mobile score 57 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Average across all dimensions


---

### PlumbSmart Plumbing Heating and Air

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://itsjustplumbsmart.com/ |
| Rating | 5.0/5 (262 reviews) |
| Phone | (623) 250-2238 |
| Address | 2550 W Union Hills Dr Suite 350-364, Phoenix, AZ 85027, USA, Phoenix, AZ, 85027 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 262 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | ServiceTitan, Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 32 | 4 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 10209 | N/A |
| var | 5519 | N/A |
| replacement | 5100 | N/A |
| repair | 4879 | N/A |
| return | 4517 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1403 | - | Good |
| Thin Content (<300) | 4 (1%) | - | Good |
| Rich Content (>1000) | 223 (96%) | - | Excellent |

**Content Distribution:**
- Service pages: 43
- Location pages: 4
- Blog posts: 184
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 99 | Excellent |
| Desktop | 89 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.7s | ≤2.5s | Pass ✓ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 6 |
| Form Labels Missing | 16 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links, 16 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 262 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 94/100 | Mobile score 99 |
| Brand | 90/100 | 19.5 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content
- Established brand presence


---

### Plumbers Near Me - Water Heater & Plumbing Services of Sun City

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (8 reviews) |
| Phone | (623) 866-5711 |
| Address | 10451 W Palmeras Dr, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 8
- Standard local operator profile: 8 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 8 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Plumbing Masters

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://plumbingmastersaz.com/?utm_source=google&utm_medium=gbp |
| Rating | 4.9/5 (3921 reviews) |
| Phone | (602) 607-1405 |
| Address | 9299 W Olive Ave Building 2, Suite 207, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 3921 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Vue.js, Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 46 | 3 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| width | 21331 | N/A |
| border | 20196 | N/A |
| text | 15513 | N/A |
| content | 13083 | N/A |
| top | 13044 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 161 | 47 | Above |
| Avg Word Count | 3293 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 161 (100%) | - | Excellent |

**Content Distribution:**
- Service pages: 66
- Location pages: 10
- Blog posts: 52
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 48 | Poor |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.2s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 5 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 5 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 3921 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 161 Pages |
| Technical | 57/100 | Mobile score 48 |
| Brand | 90/100 | 13.2 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Comprehensive content
- Established brand presence


---

### Pridemark Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://pridemarkplumbing.com/?utm_source=gmb&utm_medium=social&utm_campaign=1seo_gmb |
| Rating | 4.9/5 (316 reviews) |
| Phone | (623) 239-2606 |
| Address | 15151 W Dahlia Dr, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 316 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 3152 | N/A |
| https | 3097 | N/A |
| water | 3076 | N/A |
| true | 2904 | N/A |
| com | 2872 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 364 | 47 | Above |
| Avg Word Count | 1267 | - | Good |
| Thin Content (<300) | 134 (36%) | - | Needs Work |
| Rich Content (>1000) | 230 (63%) | - | Excellent |

**Content Distribution:**
- Service pages: 58
- Location pages: 9
- Blog posts: 10
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 38 | Poor |
| Desktop | 68 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 11.8s | ≤2.5s | Fail ✗ |
| CLS | 0.05 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 2 |
| Form Labels Missing | 4 |

**Issues:** Missing skip link, Missing lang attribute, 4 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 316 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 364 Pages |
| Technical | 53/100 | Mobile score 38 |
| Brand | 75/100 | 7.8 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content, established brand

**Strengths:**
- Strong review volume and ratings
- Comprehensive content
- Established brand presence


---

### Pro Plumbers Surprise

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (26 reviews) |
| Phone | (623) 220-5602 |
| Address | 16525 N 165th Ave, Surprise, AZ 85388, USA, Surprise, AZ, 85388 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 26 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 26 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Proforce Plumbing Sewer & Drain

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://proforceplumbing.com/ |
| Rating | 4.9/5 (75 reviews) |
| Phone | (623) 323-8800 |
| Address | 8969 W Maryland Ave, Glendale, AZ 85305, USA, Glendale, AZ, 85305 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 75 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"5.5.17"}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| menu | 6988 | N/A |
| jquery | 4003 | N/A |
| oxy | 3800 | N/A |
| pro | 3180 | N/A |
| function | 1458 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 74 | 47 | Above |
| Avg Word Count | 1373 | - | Good |
| Thin Content (<300) | 8 (10%) | - | Good |
| Rich Content (>1000) | 66 (89%) | - | Excellent |

**Content Distribution:**
- Service pages: 24
- Location pages: 7
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 65 | Needs Improvement |
| Desktop | 65 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.2s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 75 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 74 Pages |
| Technical | 65/100 | Mobile score 65 |
| Brand | 75/100 | 5.7 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: established brand

**Strengths:**
- Established brand presence


---

### Rapid Rooter Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://rapidrooteraz.com/ |
| Rating | 5.0/5 (187 reviews) |
| Phone | (623) 581-0346 |
| Address | 4123 W Saguaro Park Ln, Glendale, AZ 85310, USA, Glendale, AZ, 85310 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 187 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Housecall Pro, Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 11 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 12099 | N/A |
| function | 10004 | N/A |
| com | 8605 | N/A |
| rapidrooteraz | 7959 | N/A |
| content | 7677 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1463 | - | Good |
| Thin Content (<300) | 4 (1%) | - | Good |
| Rich Content (>1000) | 223 (96%) | - | Excellent |

**Content Distribution:**
- Service pages: 0
- Location pages: 5
- Blog posts: 1
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 41 | Poor |
| Desktop | 41 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 22.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 4 |
| Empty Links | 6 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 187 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 41/100 | Mobile score 41 |
| Brand | 90/100 | 16.3 years |

**Threat Level: HIGH**

**Assessment:** Strong in strong reputation, deep content, established brand; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content
- Established brand presence

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (41) with 80+


---

### Right On Time Plumbing & Drain

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 4.8/5 (24 reviews) |
| Phone | (623) 698-1993 |
| Address | 8133 W Hatcher Rd, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 24 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 58/100 | 24 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Rivers Plumbing Services

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.riversplumbingservices.com/ |
| Rating | 4.9/5 (39 reviews) |
| Phone | N/A |
| Address | 11352 W Primrose Dr, Avondale, AZ 85392, USA, Avondale, AZ, 85392 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 39 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 1511 | N/A |
| specs | 1500 | N/A |
| return | 894 | N/A |
| const | 736 | N/A |
| thunderbolt | 658 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 12 | 47 | Below |
| Avg Word Count | 931 | - | Good |
| Thin Content (<300) | 8 (66%) | - | Needs Work |
| Rich Content (>1000) | 4 (33%) | - | Excellent |

**Content Distribution:**
- Service pages: 12
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | 92 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 59/100 | 39 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 12 Pages |
| Technical | 71/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Roadrunner Plumber

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://roadrunnerplumber.com/ |
| Rating | 4.9/5 (108 reviews) |
| Phone | (602) 579-7612 |
| Address | 17786 W Gambit Trail, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 108 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 3 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 33 | Poor |
| Desktop | 44 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 17.4s | ≤2.5s | Fail ✗ |
| CLS | 0.80 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 108 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 38/100 | Mobile score 33 |
| Brand | 75/100 | 7.8 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in established brand; vulnerable in poor technical performance, thin content

**Strengths:**
- Established brand presence

**Weaknesses:**
- Poor mobile performance
- Thin content

**Opportunities to Exploit:**
- Beat their mobile score (33) with 80+
- Create deeper content than their thin pages


---

### Robins Plumbing Inc

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.robinsplumbing.com/ |
| Rating | 4.9/5 (1121 reviews) |
| Phone | (623) 486-4657 |
| Address | 5955 W Peoria Ave #5160, Glendale, AZ 85302, USA, Glendale, AZ, 85302 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1121 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 7 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 9486 | N/A |
| gform | 7041 | N/A |
| plumbing | 6726 | N/A |
| var | 6248 | N/A |
| content | 5560 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2202 | - | Good |
| Thin Content (<300) | 8 (3%) | - | Good |
| Rich Content (>1000) | 220 (95%) | - | Excellent |

**Content Distribution:**
- Service pages: 10
- Location pages: 14
- Blog posts: 2
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 0 |
| Avg Position | 8.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 8 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 1121 reviews |
| SERP | 3/100 | 1 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content

**Strengths:**
- Strong review volume and ratings
- Comprehensive content


---

### Rooter Ranger

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.rooterranger.com/service-areas/arizona/sun-city/?utm_source=google&utm_medium=GBP |
| Rating | 4.9/5 (311 reviews) |
| Phone | (623) 469-5841 |
| Address | 9849 W Bell Rd, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 311 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Vue.js, Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (1 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| chl | 11 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 70 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 60 | Needs Improvement |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.8s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 311 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 55/100 | Mobile score 60 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Rooter Relief Plumbing & Drains

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.rooterreliefplumbing.com/ |
| Rating | 5.0/5 (23 reviews) |
| Phone | (818) 484-0922 |
| Address | 5042 N 65th Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 23 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (8 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| astro | 21 | N/A |
| cid | 21 | N/A |
| data | 21 | N/A |
| rect | 20 | N/A |
| jlpqxutv | 13 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 156 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 69 | Needs Improvement |
| Desktop | 94 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.5s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 23 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 81/100 | Mobile score 69 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Roto-Rooter Plumbing & Water Cleanup

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.rotorooter.com/surpriseaz/?utm_source=Google&utm_medium=organic&utm_campaign=gmb&utm_content=website |
| Rating | 5.0/5 (481 reviews) |
| Phone | (602) 466-7304 |
| Address | 12133 W Bell Rd #104, Surprise, AZ 85378, USA, Surprise, AZ, 85378 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 481 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| null | 99632 | N/A |
| typename | 76215 | N/A |
| plumbing | 67408 | N/A |
| src | 41429 | N/A |
| water | 35467 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 5957 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 203 (88%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 65
- Blog posts: 41
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 36 | Poor |
| Desktop | 61 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 481 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 48/100 | Mobile score 36 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (36) with 80+


---

### Roto-Rooter Plumbing & Water Cleanup

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.rotorooter.com/suncityaz/?utm_source=Google&utm_medium=organic&utm_campaign=gmb&utm_content=website |
| Rating | 4.9/5 (315 reviews) |
| Phone | (623) 696-4812 |
| Address | 12630 N 103rd Ave # 112, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 315 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| null | 98664 | N/A |
| typename | 75176 | N/A |
| plumbing | 64895 | N/A |
| src | 40660 | N/A |
| water | 36770 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 6018 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 203 (88%) | - | Excellent |

**Content Distribution:**
- Service pages: 9
- Location pages: 60
- Blog posts: 41
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 33 | Poor |
| Desktop | 49 | Poor |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.1s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 315 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 41/100 | Mobile score 33 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (33) with 80+


---

### Roto-Rooter Plumbing & Water Cleanup

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.rotorooter.com/glendaleaz/?utm_source=Google&utm_medium=organic&utm_campaign=gmb&utm_content=website |
| Rating | 4.8/5 (2747 reviews) |
| Phone | (623) 687-2008 |
| Address | 7250 W Frier Dr #105, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 2747 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| null | 99712 | N/A |
| typename | 76302 | N/A |
| plumbing | 67409 | N/A |
| src | 41432 | N/A |
| water | 35513 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 5983 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 203 (88%) | - | Excellent |

**Content Distribution:**
- Service pages: 8
- Location pages: 65
- Blog posts: 41
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 45 | Poor |
| Desktop | 66 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.8s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 12.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 12 | organic |

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 6 |
| Empty Links | 2 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 95/100 | 2747 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 55/100 | Mobile score 45 |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content

**Strengths:**
- Strong review volume and ratings
- Comprehensive content


---

### Sav-On Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://sav-onplumbing.com/ |
| Rating | 4.8/5 (140 reviews) |
| Phone | (623) 487-9500 |
| Address | 7110 N 45th Ave, Glendale, AZ 85301, USA, Glendale, AZ, 85301 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 140 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| tve | 12606 | N/A |
| important | 9017 | N/A |
| data | 7893 | N/A |
| css | 6313 | N/A |
| message | 3846 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 1763 | - | Good |
| Thin Content (<300) | 10 (4%) | - | Good |
| Rich Content (>1000) | 208 (90%) | - | Excellent |

**Content Distribution:**
- Service pages: 31
- Location pages: 20
- Blog posts: 5
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 59 | Needs Improvement |
| Desktop | 92 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 10.5s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 6 |
| Form Labels Missing | 4 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links, 4 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 68/100 | 140 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 75/100 | Mobile score 59 |
| Brand | 90/100 | 20.6 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: good technical performance, deep content, established brand

**Strengths:**
- Good technical performance
- Comprehensive content
- Established brand presence


---

### Sav-On Plumbing - Sun City

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://sav-onplumbing.com/contact-us/service-areas/plumbing-in-sun-city-az/ |
| Rating | 4.9/5 (62 reviews) |
| Phone | (623) 537-9898 |
| Address | 9508 W Hidden Valley Cir, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 62 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| tve | 12683 | N/A |
| important | 9387 | N/A |
| data | 7980 | N/A |
| css | 6392 | N/A |
| water | 5713 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 2051 | - | Good |
| Thin Content (<300) | 16 (6%) | - | Good |
| Rich Content (>1000) | 206 (89%) | - | Excellent |

**Content Distribution:**
- Service pages: 43
- Location pages: 25
- Blog posts: 7
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 79 | Needs Improvement |
| Desktop | 95 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.5s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 62 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 87/100 | Mobile score 79 |
| Brand | 90/100 | 20.6 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: good technical performance, deep content, established brand

**Strengths:**
- Good technical performance
- Comprehensive content
- Established brand presence


---

### Set Apart Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://setapartplumbing.com/ |
| Rating | 5.0/5 (188 reviews) |
| Phone | (480) 404-0979 |
| Address | 25304 N 144th Dr, Surprise, AZ 85387, USA, Surprise, AZ, 85387 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 188 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| block | 27300 | N/A |
| sqs | 15625 | N/A |
| width | 12863 | N/A |
| grid | 11498 | N/A |
| view | 10390 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 218 | 47 | Above |
| Avg Word Count | 1693 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 215 (98%) | - | Excellent |

**Content Distribution:**
- Service pages: 19
- Location pages: 29
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 37 | Poor |
| Desktop | 57 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 19.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify JavaScript

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 70/100 | 188 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 218 Pages |
| Technical | 47/100 | Mobile score 37 |
| Brand | 35/100 | 1.5 years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, deep content; vulnerable in poor technical performance

**Strengths:**
- Strong review volume and ratings
- Comprehensive content

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (37) with 80+


---

### Sigma Pro Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.sigmaproplumb.com/ |
| Rating | 5.0/5 (27 reviews) |
| Phone | (602) 583-5649 |
| Address | 22613 N 119th Dr, Sun City, AZ 85373, USA, Sun City, AZ, 85373 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 27 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| const | 102 | N/A |
| owned | 71 | N/A |
| plumbing | 61 | N/A |
| cleaningplumbing | 54 | N/A |
| installationplumbing | 54 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 39 | 47 | Average |
| Avg Word Count | 221 | - | Thin |
| Thin Content (<300) | 28 (71%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 56 | Needs Improvement |
| Desktop | 76 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 6.8s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 2 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 27 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 39 Pages |
| Technical | 66/100 | Mobile score 56 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Average across all dimensions


---

### Smiley Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://smileyplumbing.com/ |
| Rating | 4.9/5 (70 reviews) |
| Phone | (623) 583-9400 |
| Address | 7918 W Briden Ln, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 70 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 4 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 1917 | N/A |
| document | 1408 | N/A |
| water | 1149 | N/A |
| var | 945 | N/A |
| function | 732 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 139 | 47 | Above |
| Avg Word Count | 676 | - | Average |
| Thin Content (<300) | 13 (9%) | - | Good |
| Rich Content (>1000) | 9 (6%) | - | Opportunity |

**Content Distribution:**
- Service pages: 10
- Location pages: 75
- Blog posts: 5
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 54 | Needs Improvement |
| Desktop | 70 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.1s | ≤2.5s | Fail ✗ |
| CLS | 0.06 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 69/100 | 70 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 80/100 | 139 Pages |
| Technical | 62/100 | Mobile score 54 |
| Brand | 90/100 | 22.2 years |

**Threat Level: HIGH**

**Assessment:** Strong overall: deep content, established brand

**Strengths:**
- Comprehensive content
- Established brand presence


---

### Somers Plumbers - Phoenix Plumbing Company

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.somersplumbers.net/ |
| Rating | 5.0/5 (292 reviews) |
| Phone | (480) 568-2596 |
| Address | 14039 N 8th Pl, Phoenix, AZ 85022, USA, Phoenix, AZ, 85022 |
| Review Context | Above Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 292 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 29 | 2 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| water | 3741 | N/A |
| block | 2706 | N/A |
| sqs | 1683 | N/A |
| plumbing | 1637 | N/A |
| grid | 1504 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 192 | 47 | Above |
| Avg Word Count | 1050 | - | Good |
| Thin Content (<300) | 42 (21%) | - | Needs Work |
| Rich Content (>1000) | 38 (19%) | - | Good |

**Content Distribution:**
- Service pages: 11
- Location pages: 34
- Blog posts: 157
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 38 | Poor |
| Desktop | 71 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 19.9s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 28.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 28 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Poor |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Alt text quality: Poor, Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 292 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 80/100 | 192 Pages |
| Technical | 54/100 | Mobile score 38 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, deep content

**Strengths:**
- Strong review volume and ratings
- Comprehensive content


---

### Southwest Plumbing Services LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.swplumbingservicesaz.com/ |
| Rating | 5.0/5 (45 reviews) |
| Phone | (480) 999-5678 |
| Address | 3216 N 109th Ave, Avondale, AZ 85392, USA, Avondale, AZ, 85392 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 45 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | N/A | N/A |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 45 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Spartan Plumbing Solutions LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://spartanplumbingsolutions.com/ |
| Rating | 4.9/5 (387 reviews) |
| Phone | (602) 366-9077 |
| Address | 500 N Estrella Pkwy Suite B2-173, Goodyear, AZ 85338, USA, Goodyear, AZ, 85338 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 387 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Wix static resources found"],"name":"Wix","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| true | 15809 | N/A |
| specs | 14479 | N/A |
| false | 5416 | N/A |
| return | 4480 | N/A |
| bookings | 4258 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 22 | 47 | Below |
| Avg Word Count | 1990 | - | Good |
| Thin Content (<300) | 2 (9%) | - | Good |
| Rich Content (>1000) | 20 (90%) | - | Excellent |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 75 | Needs Improvement |
| Desktop | 92 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.1s | ≤2.5s | Fail ✗ |
| CLS | 0.03 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 4 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 79/100 | 387 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 22 Pages |
| Technical | 83/100 | Mobile score 75 |
| Brand | 20/100 | 0.4 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, good technical performance

**Strengths:**
- Strong review volume and ratings
- Good technical performance


---

### Stars 48 Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.stars48plumbing.com/ |
| Rating | 5.0/5 (16 reviews) |
| Phone | (602) 499-3084 |
| Address | 13233 W Tyler Trail, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 16 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["GoDaddy Website Builder resources found"],"name":"GoDaddy Website Builder","version":null}  | Medium |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (2 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 26 | N/A |
| get | 10 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 6 | 47 | Below |
| Avg Word Count | 146 | - | Thin |
| Thin Content (<300) | 6 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 93 | Excellent |
| Desktop | 98 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 3.0s | ≤2.5s | Needs Work |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | None |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 3 |
| Empty Links | 0 |
| Form Labels Missing | 2 |

**Issues:** Alt text quality: None, Missing skip link, Missing lang attribute, 2 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 16 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 6 Pages |
| Technical | 95/100 | Mobile score 93 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in good technical performance; vulnerable in thin content

**Strengths:**
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Sun City Action Plumbers

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://bestplumberinsuncity.com/ |
| Rating | 4.7/5 (15 reviews) |
| Phone | (623) 432-1968 |
| Address | 14819 N Del Webb Blvd, Sun City, AZ 85351, USA, Sun City, AZ, 85351 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 15 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"4.9.3"}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 1 | 1 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| plumbing | 465 | N/A |
| water | 315 | N/A |
| sewer | 309 | N/A |
| services | 301 | N/A |
| repair | 249 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 64 | 47 | Above |
| Avg Word Count | 847 | - | Good |
| Thin Content (<300) | 4 (6%) | - | Good |
| Rich Content (>1000) | 11 (17%) | - | Good |

**Content Distribution:**
- Service pages: 18
- Location pages: 0
- Blog posts: 2
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 47 | Poor |
| Desktop | N/A | N/A |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 8.5s | ≤2.5s | Fail ✗ |
| CLS | 0.33 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Minify JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 2 |
| Empty Links | 1 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 57/100 | 15 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 64 Pages |
| Technical | 48/100 | Mobile score 47 |
| Brand | 90/100 | 11.9 years |

**Threat Level: HIGH**

**Assessment:** Strong in established brand; vulnerable in poor technical performance

**Strengths:**
- Established brand presence

**Weaknesses:**
- Poor mobile performance

**Opportunities to Exploit:**
- Beat their mobile score (47) with 80+


---

### Sunland Plumbing & Construction

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.sunlandpc.com/ |
| Rating | 4.7/5 (93 reviews) |
| Phone | (623) 933-4170 |
| Address | 13200 N 113th Ave #5th, Youngtown, AZ 85363, USA, Youngtown, AZ, 85363 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 93 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| obj | 9999 | N/A |
| endobj | 9994 | N/A |
| stream | 8076 | N/A |
| endstream | 7750 | N/A |
| adobed | 3096 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 56 | 47 | Average |
| Avg Word Count | 12676 | - | Good |
| Thin Content (<300) | 2 (3%) | - | Good |
| Rich Content (>1000) | 30 (53%) | - | Excellent |

**Content Distribution:**
- Service pages: 18
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 71 | Needs Improvement |
| Desktop | 96 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 67/100 | 93 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 60/100 | 56 Pages |
| Technical | 83/100 | Mobile score 71 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Sunstate Plumbing, Inc

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.sunstateplumbinginc.com/ |
| Rating | 4.8/5 (104 reviews) |
| Phone | (623) 937-4258 |
| Address | 8701 N 78th Ave, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 104 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Framework | Angular, jQuery, Bootstrap | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 47 | 16 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| var | 758 | N/A |
| plumbing | 632 | N/A |
| water | 618 | N/A |
| service | 601 | N/A |
| script | 480 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 70 | 47 | Above |
| Avg Word Count | 1170 | - | Good |
| Thin Content (<300) | 3 (4%) | - | Good |
| Rich Content (>1000) | 38 (54%) | - | Excellent |

**Content Distribution:**
- Service pages: 3
- Location pages: 2
- Blog posts: 10
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 95 | Excellent |
| Desktop | 95 | Excellent |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 1.0s | ≤2.5s | Pass ✓ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 0 |
| Top 3 Positions | 0 |
| Avg Position | 30.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 30 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 12 |
| Empty Links | 13 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 13 empty links, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 68/100 | 104 reviews |
| SERP | 1/100 | 1 keywords tracked |
| Content | 60/100 | 70 Pages |
| Technical | 95/100 | Mobile score 95 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### Surprise Plumber and Handyman

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://surpriseplumbingandhandyman.com/ |
| Rating | 5.0/5 (7 reviews) |
| Phone | (602) 643-6000 |
| Address | 13856 W Country Gables Dr, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 7
- Standard local operator profile: 7 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| code | 507 | N/A |
| name | 507 | N/A |
| phonecode | 490 | N/A |
| services | 124 | N/A |
| plumbing | 105 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 39 | 47 | Average |
| Avg Word Count | 316 | - | Thin |
| Thin Content (<300) | 24 (61%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 6
- Location pages: 39
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 60 | Needs Improvement |
| Desktop | 82 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 5.1s | ≤2.5s | Fail ✗ |
| CLS | 0.01 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 7 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 7 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 39 Pages |
| Technical | 71/100 | Mobile score 60 |
| Brand | 20/100 | 0.9 years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: good technical performance

**Strengths:**
- Good technical performance


---

### The Aussie Plumber

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.theaussieplumber.com/ |
| Rating | 5.0/5 (899 reviews) |
| Phone | (602) 820-5551 |
| Address | 4600 E Shea Blvd Ste 203, Phoenix, AZ 85028, USA, Phoenix, AZ, 85028 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 899 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| Booking | Square Appointments | High |
| Framework | Vue.js, Angular, jQuery | Medium |

#### Keyword Analysis

**Succeeding Keywords** (1 keyword capturing search demand)

| Keyword | Volume | Frequency | Pages |
|---------|--------|-----------|-------|
| repiping | 1,900 | 34 | 2 |

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| important | 3923 | N/A |
| 0rem | 3096 | N/A |
| margin | 2698 | N/A |
| padding | 2259 | N/A |
| bottom | 1140 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 122 | 47 | Above |
| Avg Word Count | 1170 | - | Good |
| Thin Content (<300) | 5 (4%) | - | Good |
| Rich Content (>1000) | 79 (64%) | - | Excellent |

**Content Distribution:**
- Service pages: 64
- Location pages: 8
- Blog posts: 3
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 54 | Needs Improvement |
| Desktop | 81 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 15.5s | ≤2.5s | Fail ✗ |
| CLS | 0.08 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### SERP Rankings

**Overview**

| Metric | Value |
|--------|-------|
| Keywords Tracked | 1 |
| Page 1 Rankings | 1 |
| Top 3 Positions | 0 |
| Avg Position | 7.0 |

**Top Rankings**

| Keyword | Position | Type |
|---------|----------|------|
| plumber near Phoenix, AZ | 7 | organic |

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 10 |
| Empty Links | 6 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, 6 empty links

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 90/100 | 899 reviews |
| SERP | 3/100 | 1 keywords tracked |
| Content | 80/100 | 122 Pages |
| Technical | 67/100 | Mobile score 54 |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, deep content

**Strengths:**
- Strong review volume and ratings
- Comprehensive content


---

### The Family Plumber, LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.callthefamilyplumber.com/?utm_source=GMBlisting&utm_medium=Organic&utm_campaign=GMBwebsite |
| Rating | 5.0/5 (378 reviews) |
| Phone | (623) 738-6171 |
| Address | 17675 W Pershing St, Surprise, AZ 85388, USA, Surprise, AZ, 85388 |
| Review Context | Above 75th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 378 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":"6.9"}  | Medium |
| Booking | Housecall Pro | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| obj | 2955 | N/A |
| endobj | 2951 | N/A |
| xmp | 2372 | N/A |
| water | 2316 | N/A |
| plumbing | 1727 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 284 | 47 | Above |
| Avg Word Count | 5385 | - | Good |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 136 (47%) | - | Excellent |

**Content Distribution:**
- Service pages: 9
- Location pages: 25
- Blog posts: 3
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 39 | Poor |
| Desktop | 67 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 18.4s | ≤2.5s | Fail ✗ |
| CLS | 0.32 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Minify CSS

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 5 |
| Empty Links | 2 |
| Form Labels Missing | 1 |

**Issues:** Missing skip link, Missing lang attribute, 1 form fields missing labels

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 80/100 | 378 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 284 Pages |
| Technical | 53/100 | Mobile score 39 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong overall: strong reputation, deep content

**Strengths:**
- Strong review volume and ratings
- Comprehensive content


---

### The Plumber Guy

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.theplumberguy.com/ |
| Rating | 4.9/5 (3392 reviews) |
| Phone | (623) 233-4350 |
| Address | 9162 W Cactus Rd ste c, Peoria, AZ 85381, USA, Peoria, AZ, 85381 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Enterprise Network |
| Confidence | 80% |

**Evidence:**
- High review count: 3392 (threshold: 2000)

*Note: This competitor operates in a different competitive class than local operators. Direct comparison may be misleading.*

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["wp-content/wp-includes paths found"],"name":"WordPress","version":null}  | Medium |
| Booking | Square Appointments | High |
| Framework | Angular, jQuery | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| function | 27740 | N/A |
| var | 18251 | N/A |
| jquery | 16207 | N/A |
| gform | 13735 | N/A |
| return | 13710 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 230 | 47 | Above |
| Avg Word Count | 3504 | - | Good |
| Thin Content (<300) | 6 (2%) | - | Good |
| Rich Content (>1000) | 220 (95%) | - | Excellent |

**Content Distribution:**
- Service pages: 67
- Location pages: 75
- Blog posts: 117
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 73 | Needs Improvement |
| Desktop | 88 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.4s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 3 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 96/100 | 3392 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 95/100 | 230 Pages |
| Technical | 80/100 | Mobile score 73 |
| Brand | 20/100 | N/A years |

**Threat Level: HIGH**

**Assessment:** Strong overall: strong reputation, good technical performance, deep content

**Strengths:**
- Strong review volume and ratings
- Good technical performance
- Comprehensive content


---

### The Plumber Guy

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (2 reviews) |
| Phone | N/A |
| Address | Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 2
- Standard local operator profile: 2 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 2 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### The Trusted Plumber

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.thetrustedplumber.com/ |
| Rating | 4.7/5 (31 reviews) |
| Phone | (623) 201-4565 |
| Address | 7611 N 74th Ave #2, Glendale, AZ 85303, USA, Glendale, AZ, 85303 |
| Review Context | Below Median |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 31 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 37 | Poor |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 16.5s | ≤2.5s | Fail ✗ |
| CLS | 0.29 | ≤0.1 | Fail ✗ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 57/100 | 31 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 46/100 | Mobile score 37 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: poor technical performance, thin content

**Weaknesses:**
- Poor mobile performance
- Thin content

**Opportunities to Exploit:**
- Beat their mobile score (37) with 80+
- Create deeper content than their thin pages


---

### Tom's Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 3.7/5 (3 reviews) |
| Phone | (623) 933-6363 |
| Address | 5323 N Tuthill Rd, Litchfield Park, AZ 85340, USA, Litchfield Park, AZ, 85340 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 3
- Standard local operator profile: 3 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 47/100 | 3 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Trident Plumbing & Drain

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.tridentplumbingllc.com/service-areas/peoria-az/?utm_source=gbp&utm_medium=organic&utm_campaign=peoria |
| Rating | 5.0/5 (1277 reviews) |
| Phone | (623) 879-2020 |
| Address | 26134 N 121st Ave, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Statistical Outlier ⚠ |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Regional Brand |
| Confidence | 50% |

**Evidence:**
- Regional review count: 1277 (range: 500-2000)

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 106 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 2
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 73 | Needs Improvement |
| Desktop | 83 | Good |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 4.7s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Initial server response time was short

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 97/100 | 1277 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 78/100 | Mobile score 73 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Strong in strong reputation, good technical performance; vulnerable in thin content

**Strengths:**
- Strong review volume and ratings
- Good technical performance

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Vintage Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | https://www.vintageplumbingaz.com/ |
| Rating | 5.0/5 (13 reviews) |
| Phone | (602) 872-6774 |
| Address | 15152 W Calavar Rd, Surprise, AZ 85379, USA, Surprise, AZ, 85379 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 13 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|
| CMS | {"confidence":"High","evidence":["Squarespace resources found"],"name":"Squarespace","version":null}  | Medium |
| Framework | Angular | Medium |

#### Keyword Analysis

**Wasteful Keywords** (30 keyword low/no search demand)

| Keyword | Frequency | Volume |
|---------|-----------|--------|
| name | 756 | N/A |
| code | 750 | N/A |
| phonecode | 735 | N/A |
| block | 556 | N/A |
| sqs | 369 | N/A |

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 24 | 47 | Below |
| Avg Word Count | 933 | - | Good |
| Thin Content (<300) | 3 (12%) | - | Good |
| Rich Content (>1000) | 6 (25%) | - | Excellent |

**Content Distribution:**
- Service pages: 3
- Location pages: 0
- Blog posts: 0
- Sitemap: Yes
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 53 | Needs Improvement |
| Desktop | 56 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 21.3s | ≤2.5s | Fail ✗ |
| CLS | 0.00 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused CSS
- Reduce unused JavaScript
- Initial server response time was short

#### ADA Compliance

**Status:** Minor Issues

| Check | Status |
|-------|--------|
| Alt Text | Good |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Present |
| ARIA Landmarks | 8 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 13 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 40/100 | 24 Pages |
| Technical | 54/100 | Mobile score 53 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Average across all dimensions


---

### Ward Plumbing & Drain Service LLC.

#### Overview

| Metric | Value |
|--------|-------|
| Website | http://www.wardplumbingservices.com/ |
| Rating | 4.7/5 (12 reviews) |
| Phone | (623) 298-9643 |
| Address | 7407 N 185th Ave, Waddell, AZ 85355, USA, Waddell, AZ, 85355 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 12 reviews

#### Technology Stack

| Category | Technology | Confidence |
|----------|------------|------------|

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 2 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 2 (100%) | - | Needs Work |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 2
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: Yes

#### Technical Performance

**Lighthouse Scores**

| Device | Score | Rating |
|--------|-------|--------|
| Mobile | 57 | Needs Improvement |
| Desktop | 64 | Needs Improvement |

**Core Web Vitals (Mobile)**

| Metric | Value | Threshold | Status |
|--------|-------|-----------|--------|
| LCP | 9.0s | ≤2.5s | Fail ✗ |
| CLS | 0.02 | ≤0.1 | Pass ✓ |

**Improvement Opportunities:**
- Reduce unused JavaScript
- Initial server response time was short
- Avoid multiple page redirects

#### ADA Compliance

**Status:** Non-Compliant

| Check | Status |
|-------|--------|
| Alt Text | Unknown |
| Skip Link | Missing |
| Lang Attribute | Missing |
| H1 Heading | Missing |
| ARIA Landmarks | 0 |
| Empty Links | 0 |
| Form Labels Missing | 0 |

**Issues:** Missing skip link, Missing lang attribute, No H1 heading

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 57/100 | 12 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 2 Pages |
| Technical | 60/100 | Mobile score 57 |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Water Fighters Plumbing

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (15 reviews) |
| Phone | (602) 884-5325 |
| Address | 23241 N 87th Dr, Peoria, AZ 85383, USA, Peoria, AZ, 85383 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 15 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 15 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Xcel Plumbing Glendale

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (24 reviews) |
| Phone | (480) 264-8585 |
| Address | 5905 W Bell Rd #198, Glendale, AZ 85308, USA, Glendale, AZ, 85308 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Standard local operator profile: 24 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 24 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

### Xtreme Plumbing LLC

#### Overview

| Metric | Value |
|--------|-------|
| Website | N/A |
| Rating | 5.0/5 (5 reviews) |
| Phone | (480) 709-1143 |
| Address | 9027 W Griswold Rd, Peoria, AZ 85345, USA, Peoria, AZ, 85345 |
| Review Context | Below 25th Percentile |

#### Entity Classification

| Attribute | Value |
|-----------|-------|
| Class | Local Operator |
| Confidence | 60% |

**Evidence:**
- Very low review count: 5
- Standard local operator profile: 5 reviews

#### Keyword Analysis

**Missed Opportunities** (30 high-volume keywords not targeted)

| Keyword | Volume | Category |
|---------|--------|----------|
| plumber near me | 450,000 | general |
| emergency plumber | 90,500 | emergency |
| plumbing services | 40,500 | general |
| 24 hour plumber | 33,100 | emergency |
| drain cleaning | 27,100 | drain_cleaning |

#### Content Analysis

| Metric | Value | Market Avg | Rating |
|--------|-------|------------|--------|
| Total Pages | 0 | 47 | Below |
| Avg Word Count | 0 | - | Thin |
| Thin Content (<300) | 0 (0%) | - | Good |
| Rich Content (>1000) | 0 (0%) | - | Opportunity |

**Content Distribution:**
- Service pages: 0
- Location pages: 0
- Blog posts: 0
- Sitemap: No
- Robots.txt: No

#### Competitive Assessment

**Competitive Power Analysis**

| Dimension | Score | Context |
|-----------|-------|---------|
| Reputation | 60/100 | 5 reviews |
| SERP | 0/100 | 0 keywords tracked |
| Content | 20/100 | 0 Pages |
| Technical | 50/100 | Mobile score N/A |
| Brand | 20/100 | N/A years |

**Threat Level: MEDIUM**

**Assessment:** Weak overall: thin content

**Weaknesses:**
- Thin content

**Opportunities to Exploit:**
- Create deeper content than their thin pages


---

---

## 6. Cross-Competitor Analysis

### 6.1 Technology Adoption Trends

**CMS/Platform Distribution:**

| Platform | Count | % |
|----------|-------|---|
| WordPress | 39 | 40% |
| Angular | 30 | 30% |
| GoDaddy Website Builder | 5 | 5% |
| Squarespace | 5 | 5% |
| Wix | 5 | 5% |
| Vue.js | 4 | 4% |
| cloudflare (server) | 3 | 3% |
| Custom | 2 | 2% |
| nginx (server) | 1 | 1% |
| Sucuri/Cloudproxy (server) | 1 | 1% |

### 6.2 Performance Distribution

**Mobile Score Distribution:**

| Range | Count | % |
|-------|-------|---|
| Poor (0-49) | 32 | 31% |
| Needs Improvement (50-79) | 56 | 55% |
| Good (80-89) | 5 | 5% |
| Excellent (90+) | 9 | 9% |

### 6.3 Competitive Clustering

Based on entity classification and competitive power analysis:

| Cluster | Count | Description |
|---------|-------|-------------|
| Local Operators | 96 | Single location, <500 reviews |
| Regional Brands | 18 | Multiple locations or 500-2000 reviews |
| Enterprise Networks | 8 | Large operations, >2000 reviews |
| Brand Aggregators | 0 | Multi-service companies |

---

## 7. ADA Compliance Analysis

Website accessibility (ADA compliance) is increasingly important for both legal risk and SEO ranking. Google considers accessibility signals in search rankings.

### 7.1 Market-Wide Compliance Issues

| Issue | Count | % of Sites |
|-------|-------|------------|
| Poor/No Alt Text | 19 | 24% |
| Missing Skip Links | 78 | 100% |
| No H1 Heading | 17 | 22% |
| Empty Links (>3) | 21 | 27% |
| Form Fields Missing Labels | 24 | 31% |

### 7.2 Competitors with Multiple ADA Issues

| Competitor | Reviews | Issues |
|------------|---------|--------|
| Plumbing Masters | 3921 | Alt text: None, 5 empty links |
| Christian Brothers Plumbing, A/C, & Electrical | 2105 | 5 empty links, 8 form fields missing labels |
| 100% Plumbing | 1595 | Alt text: None, 7 form fields missing labels |
| Grand Canyon Home Services | 331 | Alt text: None, 6 empty links |
| Patriotic Plumbing And Rooter | 293 | 13 empty links, 1 form fields missing labels |
| PlumbSmart Plumbing Heating and Air | 262 | 6 empty links, 16 form fields missing labels |
| Phay Plumbing services LLC | 253 | Alt text: None, 7 form fields missing labels |
| Pink Plumbing and Sewer | 189 | Alt text: None, No H1 heading |
| All Drains Emergency Plumbing | 186 | 9 empty links, 3 form fields missing labels |
| Hotrod plumbing | 159 | Alt text: None, 16 empty links, 1 form fields missing labels |
| POP Plumbing LLC - Glendale | 155 | 9 empty links, 3 form fields missing labels |
| Sav-On Plumbing | 140 | 6 empty links, 4 form fields missing labels |
| Alpha-Plumbing Services | 113 | Alt text: None, 1 form fields missing labels |
| Forrest Anderson Plumbing & Air Conditioning | 108 | No H1 heading, 11 form fields missing labels |
| Sunstate Plumbing, Inc | 104 | 13 empty links, 1 form fields missing labels |

*Note: ADA non-compliance creates legal liability. Serial ADA litigants actively target businesses with accessibility issues.*

---

## 8. Appendices

### Appendix A: Data Dictionary

| Field | Description |
|-------|-------------|
| place_id | Google's unique identifier for a business |
| review_count | Total Google reviews at time of collection |
| mobile_score | Lighthouse performance score (0-100) |
| LCP | Largest Contentful Paint - time until largest element loads |
| INP | Interaction to Next Paint - responsiveness metric |
| CLS | Cumulative Layout Shift - visual stability metric |

### Appendix B: Glossary

**Core Web Vitals:** Google's three key metrics for user experience: LCP, INP, CLS.

**IQR (Interquartile Range):** Q3 - Q1. Used for outlier detection.

**Entity Classification:** Categorization of competitors by scale and market position.

**Boilerplate:** Repeated content appearing on multiple pages (nav, footer, etc.).

### Appendix C: Reproducibility

**Tool:** plumber (Rust CLI)

**Data Collection Commands:**
```bash
# Discover competitors
plumber research discover --zip-codes "85301,85374,..."

# Crawl websites
plumber crawl all --max-pages 50

# Analyze performance
plumber analyze performance --all

# Generate report
plumber research ai-report comprehensive
```

---

*Report generated by Plumber Market Research Platform*

---

**Prepared by [South City Computer](https://southcitycomputer.com)**

Copyright 2026 [South City Computer](https://southcitycomputer.com). All rights reserved.

This research data is proprietary and confidential. Unauthorized reproduction or distribution is prohibited.
