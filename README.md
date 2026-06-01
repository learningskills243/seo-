Act as an advanced GEO (Generative Engine Optimization) and Schema.org expert.

Analyze the website: [PASTE WEBSITE URL]

Tasks:

1. Crawl and analyze the homepage and key pages.

2. Detect all existing structured data:

   * JSON-LD
   * Microdata
   * RDFa

3. Audit the structured data for:

   * Valid Schema.org types
   * Missing required properties
   * Missing recommended properties
   * Invalid URLs
   * Missing sameAs links
   * Missing author entities
   * Missing organization entities
   * Missing LocalBusiness, Product, Article, FAQPage, SoftwareApplication, BreadcrumbList, and WebSite schemas where applicable

4. Evaluate the website for GEO (AI Search) readiness:

   * Entity recognition strength
   * Knowledge graph signals
   * Author authority signals
   * Organization authority signals
   * sameAs completeness
   * Topic authority and expertise signals
   * AI citation potential

5. Create a GEO Schema Score (0-100) based on:

   * Organization schema completeness
   * Person/Author schema completeness
   * sameAs coverage
   * JSON-LD implementation
   * Business-specific schema coverage
   * Breadcrumb schema
   * SearchAction schema
   * knowsAbout usage
   * speakable usage
   * Structured data quality

6. Generate a report in this format:

# GEO-SCHEMA-AUDIT

## Overall GEO Score

## Detected Schemas

## Validation Errors

## Missing GEO Signals

## sameAs Audit

## Entity SEO Gaps

## AI Discoverability Issues

## Recommended Schema Additions

## Ready-to-Implement JSON-LD Code

Generate complete JSON-LD using @graph format with:

* Organization
* Person/Author
* WebSite + SearchAction
* BreadcrumbList
* LocalBusiness (if applicable)
* Article (if applicable)
* Product (if applicable)
* FAQPage (if applicable)

Provide production-ready JSON-LD code and explain exactly where it should be implemented.
