# Schema.org Implementation Checklist

## Introduction

Structured data helps search engines understand the meaning of content through standardized vocabulary defined by Schema.org.

This checklist is intended to help developers and SEO professionals implement, validate, and maintain structured data that accurately reflects visible page content.

> **Important:** Structured data should always describe what users can actually see on the page.

---

# General Checklist

- [ ] JSON-LD format used.
- [ ] JSON is valid.
- [ ] UTF-8 encoding used.
- [ ] Schema matches visible content.
- [ ] Required properties reviewed.
- [ ] URLs are absolute.
- [ ] No placeholder values remain.
- [ ] Duplicate structured data avoided.
- [ ] Structured data updated when page content changes.

---

# Organization Schema

Applicable for identifying the website publisher.

- [ ] Organization name provided.
- [ ] Website URL provided.
- [ ] Logo URL valid.
- [ ] Description reviewed.
- [ ] Contact information reviewed (if included).
- [ ] Social profile URLs verified (if included).

---

# WebSite Schema

- [ ] Website name provided.
- [ ] Homepage URL correct.
- [ ] Publisher relationship reviewed.
- [ ] SearchAction implemented only if supported.
- [ ] Search URL template verified.

---

# WebPage Schema

- [ ] Page title matches visible title.
- [ ] Canonical URL reviewed.
- [ ] Description reviewed.
- [ ] Breadcrumb relationship verified (if applicable).

---

# CollectionPage Schema

Useful for category pages.

Examples:

- Railway Jobs
- SSC Jobs
- Banking Jobs

Checklist:

- [ ] Category title reviewed.
- [ ] Canonical URL verified.
- [ ] Collection accurately represents page content.

---

# Article Schema

- [ ] Headline reviewed.
- [ ] Author information verified (if included).
- [ ] Publication date correct.
- [ ] Modified date updated.
- [ ] Featured image URL verified.
- [ ] Description reviewed.

---

# JobPosting Schema

Only use where the page genuinely represents an individual job opportunity.

- [ ] Job title reviewed.
- [ ] Hiring organization identified.
- [ ] Job location reviewed.
- [ ] Employment type reviewed.
- [ ] Date posted verified.
- [ ] Valid through date reviewed.
- [ ] Identifier verified (if used).

---

# FAQPage Schema

Only use when FAQs are visible on the page.

- [ ] Questions match visible headings.
- [ ] Answers match visible content.
- [ ] Duplicate FAQs avoided.
- [ ] FAQ content reviewed for accuracy.

---

# BreadcrumbList Schema

- [ ] Breadcrumb hierarchy matches navigation.
- [ ] Positions sequential.
- [ ] URLs valid.
- [ ] Labels descriptive.

---

# ImageObject

Where applicable:

- [ ] Image URL valid.
- [ ] Image accessible.
- [ ] Appropriate dimensions used.
- [ ] Image represents visible content.

---

# JSON-LD Validation

Before deployment:

- [ ] JSON syntax validated.
- [ ] No trailing commas.
- [ ] Quotes escaped correctly.
- [ ] Arrays formatted correctly.
- [ ] Nested objects reviewed.

---

# Schema Validation

Before publishing:

- [ ] Validate JSON-LD.
- [ ] Confirm visible content matches structured data.
- [ ] Review required properties.
- [ ] Review recommended properties.
- [ ] Remove obsolete schema.

---

# Deployment Checklist

- [ ] Production page updated.
- [ ] Structured data deployed.
- [ ] Validation completed.
- [ ] XML Sitemap reviewed if necessary.
- [ ] Internal links checked.

---

# Maintenance Checklist

Monthly review:

- [ ] Publication dates updated where appropriate.
- [ ] Modified dates reviewed.
- [ ] Broken URLs fixed.
- [ ] Logo URLs verified.
- [ ] Contact information updated.
- [ ] Structured data reflects current page content.

---

# Common Mistakes

Avoid:

- Invalid JSON syntax.
- Using schema unrelated to the page.
- Hidden FAQ content.
- Placeholder values.
- Incorrect dates.
- Missing required properties.
- Duplicate schema blocks.
- Outdated structured data.

---

# Recommended Workflow

```text
Create Page

↓

Choose Appropriate Schema

↓

Generate JSON-LD

↓

Validate Syntax

↓

Compare with Visible Content

↓

Deploy

↓

Monitor

↓

Update When Content Changes
```

---

# Related Documentation

- docs/schema.md
- docs/seo.md
- examples/Organization.json
- examples/WebSite.json
- examples/Breadcrumb.json
- examples/FAQPage.json
- examples/JobPosting.json

---

# Conclusion

Structured data should improve the machine-readable understanding of a page without replacing clear, helpful content.

A disciplined validation process helps ensure structured data remains accurate as the website evolves.