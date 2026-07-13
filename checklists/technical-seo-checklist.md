# Technical SEO Checklist

## Introduction

Technical SEO is the process of optimizing a website's infrastructure so that search engines can efficiently crawl, render, index, and understand its content.

Unlike content optimization, technical SEO focuses on the health and accessibility of the website.

This checklist provides a practical reference for developers, SEO professionals, and website owners.

---

# Website Accessibility

- [ ] Website uses HTTPS.
- [ ] SSL certificate is valid.
- [ ] HTTP redirects to HTTPS.
- [ ] WWW and non-WWW versions resolve consistently.
- [ ] No mixed-content warnings.
- [ ] Website is publicly accessible.

---

# URL Structure

- [ ] URLs are readable.
- [ ] URLs use lowercase letters.
- [ ] Hyphens are used instead of underscores.
- [ ] URLs are descriptive.
- [ ] Dynamic parameters are minimized where possible.
- [ ] Duplicate URLs are avoided.

Example

Good

```
/ssc-cgl-notification-2026
```

Poor

```
/page?id=234&type=jobs
```

---

# XML Sitemap

- [ ] XML Sitemap exists.
- [ ] Sitemap is valid XML.
- [ ] Sitemap contains canonical URLs only.
- [ ] Sitemap excludes broken pages.
- [ ] Sitemap excludes redirected URLs.
- [ ] Sitemap is automatically updated.
- [ ] Sitemap is referenced in robots.txt.

---

# robots.txt

- [ ] robots.txt exists.
- [ ] robots.txt is publicly accessible.
- [ ] Sitemap directive included.
- [ ] Important public pages are crawlable.
- [ ] Administrative areas reviewed.
- [ ] robots.txt syntax validated.

---

# HTTP Status Codes

- [ ] Important pages return HTTP 200.
- [ ] Removed pages return 404 or 410 appropriately.
- [ ] Permanent redirects use 301.
- [ ] Temporary redirects use 302 only when appropriate.
- [ ] No redirect chains.
- [ ] No redirect loops.

---

# Canonical URLs

- [ ] Canonical tag exists where appropriate.
- [ ] Canonical URLs point to preferred versions.
- [ ] Duplicate pages reviewed.
- [ ] Canonical URLs are absolute.

---

# Page Titles

- [ ] Every page has a unique title.
- [ ] Titles clearly describe page content.
- [ ] Titles avoid unnecessary repetition.
- [ ] Important information appears early.

---

# Meta Descriptions

- [ ] Every important page has a meta description.
- [ ] Descriptions summarize the page accurately.
- [ ] Duplicate descriptions avoided.
- [ ] No misleading descriptions.

---

# Heading Structure

- [ ] One H1 per page.
- [ ] Logical H2 hierarchy.
- [ ] H3 headings used appropriately.
- [ ] Heading order is consistent.

---

# Internal Linking

- [ ] Every page has internal links.
- [ ] No orphan pages.
- [ ] Anchor text is descriptive.
- [ ] Related resources connected.
- [ ] Navigation reviewed.

---

# Images

- [ ] Images compressed.
- [ ] Modern image formats used where appropriate.
- [ ] Alt text provided.
- [ ] File names descriptive.
- [ ] Lazy loading implemented where appropriate.

---

# Structured Data

- [ ] JSON-LD syntax valid.
- [ ] Structured data matches visible content.
- [ ] Required properties reviewed.
- [ ] Schema validated.

---

# Mobile Optimization

- [ ] Responsive layout.
- [ ] Mobile navigation tested.
- [ ] Text readable.
- [ ] Buttons touch-friendly.
- [ ] Horizontal scrolling avoided.

---

# Core Web Vitals

- [ ] Largest Contentful Paint reviewed.
- [ ] Interaction to Next Paint reviewed.
- [ ] Cumulative Layout Shift reviewed.
- [ ] Render-blocking resources minimized.
- [ ] Images optimized.

---

# Crawlability

- [ ] Internal links accessible.
- [ ] Broken links fixed.
- [ ] Sitemap updated.
- [ ] robots.txt reviewed.
- [ ] No accidental crawl blocks.

---

# Indexability

- [ ] Important pages eligible for indexing.
- [ ] Canonical configuration reviewed.
- [ ] Duplicate content evaluated.
- [ ] Structured data validated.

---

# Security

- [ ] HTTPS enforced.
- [ ] Security headers reviewed.
- [ ] Software dependencies updated.
- [ ] Sensitive pages protected.

---

# Accessibility

- [ ] Alt text added.
- [ ] Keyboard navigation reviewed.
- [ ] Color contrast checked.
- [ ] Semantic HTML used.
- [ ] Form labels present.

---

# Performance

- [ ] CSS optimized.
- [ ] JavaScript optimized.
- [ ] Images optimized.
- [ ] Browser caching configured.
- [ ] Compression enabled.

---

# Monitoring

- [ ] Webmaster tools configured.
- [ ] Analytics configured.
- [ ] Crawl errors reviewed.
- [ ] Broken links monitored.
- [ ] Performance monitored.

---

# Before Publishing

- [ ] Metadata completed.
- [ ] Internal links checked.
- [ ] Structured data validated.
- [ ] XML Sitemap updated.
- [ ] Mobile tested.
- [ ] Accessibility reviewed.
- [ ] Performance reviewed.

---

# Monthly Technical SEO Audit

- [ ] Check crawl errors.
- [ ] Review indexing status.
- [ ] Validate structured data.
- [ ] Check broken links.
- [ ] Review redirects.
- [ ] Update XML Sitemap.
- [ ] Review robots.txt.
- [ ] Audit Core Web Vitals.
- [ ] Review canonical URLs.
- [ ] Refresh outdated pages.

---

# Related Documentation

- docs/seo.md
- docs/schema.md
- docs/sitemap.md
- docs/robots.md
- diagrams/website-architecture.md
- diagrams/crawling-process.md
- diagrams/indexing-process.md

---

# Conclusion

Technical SEO is an ongoing process rather than a one-time task.

Regular audits, continuous monitoring, and thoughtful improvements help maintain a technically healthy website that is easier for users and search engines to navigate.