# Technical SEO Audit — Adil Dent Clinics

**Independent Technical SEO Case Study | November 2026**

**Audited Website:** [Adil Dent Clinics](https://adildentclinics.com/)  
**Prepared by:** Michel — SEO Specialist  
**Focus:** Technical SEO · International SEO · Crawlability · Indexability · On-Page SEO

## Project Overview

This project presents an independent technical SEO audit of Adil Dent Clinics, a multilingual dental healthcare website serving local and international patients in Istanbul, Türkiye.

The objective was to evaluate the website's technical SEO foundation, identify potential issues affecting search visibility and user experience, and develop actionable recommendations based on crawl data and manual verification.

The audit covers:

- Crawlability and HTTP response codes
- Indexability and canonical tags
- International SEO and hreflang implementation
- Page titles, meta descriptions, and heading structure
- Structured data validation
- Internal linking opportunities
- Mobile and desktop performance

**[View the Full Technical SEO Audit (PDF)](./Technical-SEO-Audit-Adil-Dent.pdf)**

## Audit Scope

| Metric | Result |
|---|---|
| Spider Mode crawl | 500 URLs |
| Internal HTML pages analyzed | 341 |
| XML sitemap URLs tested | 411 |
| Sitemap URL responses | 100% HTTP 2xx |
| Languages assessed | English, Turkish, Arabic |
| Audit period | November 2026 |

The crawl was performed using the free version of Screaming Frog SEO Spider, which limits individual crawls to 500 URLs.

## Tools Used

| Tool | Purpose |
|---|---|
| Screaming Frog SEO Spider | Crawling, HTTP status codes, metadata, canonicals, hreflang, internal linking |
| Google PageSpeed Insights | Mobile and desktop Lighthouse performance analysis |
| Google Rich Results Test | Structured data validation |
| Safari Developer Tools | HTML inspection and rendered DOM verification |
| Manual Browser Testing | Validation of identified issues |

## Key Technical Findings

### 1. Page Performance — High Priority

An initial Google PageSpeed Insights test identified a homepage mobile Largest Contentful Paint (LCP) of **6.4 seconds**, exceeding Google's recommended 2.5-second threshold.

The audit identified potential optimization opportunities involving the homepage hero image, render-blocking CSS, and image sizing.

**Recommendation:** Investigate LCP resource loading, optimize relevant images and CSS delivery, and validate improvements through repeat testing.

*Note: Lighthouse results are laboratory measurements and can vary between test runs. Real-user performance data was unavailable.*

### 2. Broken External Links — Medium Priority

Four external NHS resources returned HTTP 404 errors during the audit.

Affected topics included cosmetic dentistry, dental X-rays, dental implants, and health records.

**Recommendation:** Replace outdated external references with relevant, functioning resources or remove them where appropriate.

### 3. Indexability and Hreflang — Medium Priority

Screaming Frog flagged five URLs in its **Noindex Return Links** hreflang report.

The affected URLs included gallery and health tourism authorization pages.

**Recommendation:** Review the indexing strategy for these pages and verify that hreflang relationships reference appropriate indexable, canonical language alternatives.

### 4. Metadata and Headings — Low Priority

Across 341 internal HTML pages:

| Finding | Count |
|---|---:|
| Page titles exceeding 60 characters | 196 |
| Meta descriptions exceeding 155 characters | 234 |
| H1 headings exceeding 70 characters | 137 |
| Duplicate H1 values flagged | 4 |

All 341 analyzed HTML pages contained exactly one H1 heading.

The duplicate H1 values were manually reviewed and identified as legitimate doctor names appearing across language versions, rather than actionable SEO issues.

**Recommendation:** Prioritize important service pages for selective metadata improvements. Length-based flags should not automatically be treated as errors.

### 5. Structured Data — Low Priority

Google's Rich Results Test identified two valid structured data items on the homepage:

- Local Business, using Dentist and MedicalClinic schema types
- Organization

No critical errors were reported. One optional `priceRange` property was missing from the Local Business markup.

**Recommendation:** Retain the valid structured data implementation and consider adding the optional property only when accurate information is available.

### 6. Internal Linking — Low Priority

An opportunity was identified to connect the main emergency dentistry service page with a relevant supporting article.

- [Emergency Dentistry Service Page](https://adildentclinics.com/emergency/)
- [Emergency Dentistry Guide](https://adildentclinics.com/blog/emergency-dentist-istanbul-night-weekend/)

Screaming Frog inlink analysis and manual inspection of the rendered DOM did not identify a direct link from the service page to the supporting guide at the time of testing.

**Recommendation:** Add a natural contextual link to improve content discoverability and strengthen the relationship between commercial and informational content.

## Methodology

The assessment followed a structured workflow:

1. **Website crawling:** Analyze the site's technical structure using Screaming Frog Spider Mode.
2. **Sitemap verification:** Test 411 XML sitemap URLs in List Mode and review their HTTP responses.
3. **Technical analysis:** Examine indexability, canonical tags, hreflang annotations, metadata, and headings.
4. **Manual verification:** Validate selected findings using browser inspection and developer tools.
5. **Performance and structured data testing:** Evaluate selected pages using Google's diagnostic tools.
6. **Prioritization:** Classify findings according to their potential impact and recommend practical corrective actions.

## Audit Limitations

This was an external assessment using publicly accessible information.

- Spider Mode was limited to 500 URLs.
- No access was available to Google Search Console, Google Analytics, server logs, or the website's CMS.
- Performance findings were based on laboratory testing rather than verified real-user measurements.
- Some observations may not represent the entire website.
- No changes were implemented on the audited website.

## Full Report

The complete PDF contains detailed findings, supporting screenshots, verification steps, and recommendations.

**[Read the Complete Technical SEO Audit](./Technical-SEO-Audit-Adil-Dent.pdf)**

## Disclaimer

This is an independent portfolio project conducted for educational and professional demonstration purposes.

The audit was not commissioned by, sponsored by, or affiliated with Adil Dent Clinics. All findings reflect publicly accessible information observed during the assessment in November 2026.

---

**Author:** Michel  
**Specialization:** Technical SEO · On-Page SEO · International SEO · Website Auditing
