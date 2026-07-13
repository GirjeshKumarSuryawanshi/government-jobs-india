# SEO Meta Tags Template

> A reusable HTML metadata template for SEO, social sharing, and structured data integration.
>
> Replace all placeholders (`{{ }}`) before deployment.

---

# HTML Template

```html
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1">

<title>{{ PAGE_TITLE }}</title>

<meta name="description" content="{{ META_DESCRIPTION }}">

<meta name="robots" content="index,follow">

<link rel="canonical" href="{{ PAGE_URL }}">

<meta name="author" content="{{ AUTHOR }}">

<meta name="theme-color" content="#2563eb">

<link rel="icon" href="/favicon.ico">

</head>

<body>

</body>

</html>
```

---

# Page Title

Checklist

- [ ] Unique title
- [ ] Clearly describes the page
- [ ] Important topic appears naturally
- [ ] Matches visible page content
- [ ] Avoids unnecessary repetition

Example

```
SSC CGL 2026 Notification – Eligibility, Vacancy & Apply Online
```

---

# Meta Description

Checklist

- [ ] Summarizes the page accurately
- [ ] Encourages clicks naturally
- [ ] Matches visible content
- [ ] Unique for important pages
- [ ] No misleading claims

Example

```
Read the SSC CGL 2026 notification including eligibility, vacancies, important dates, application process, salary, and official links.
```

---

# Canonical URL

Example

```html
<link rel="canonical" href="https://example.com/ssc-cgl-2026-notification">
```

Checklist

- [ ] Absolute URL
- [ ] Preferred page version
- [ ] Matches sitemap URL
- [ ] No tracking parameters

---

# Robots Meta

Example

```html
<meta name="robots" content="index,follow">
```

Common values

```
index,follow

noindex,nofollow

index,nofollow

noindex,follow
```

Choose values appropriate for the page's purpose.

---

# Open Graph Tags

```html
<meta property="og:type" content="article">

<meta property="og:title" content="{{ PAGE_TITLE }}">

<meta property="og:description" content="{{ META_DESCRIPTION }}">

<meta property="og:url" content="{{ PAGE_URL }}">

<meta property="og:image" content="{{ FEATURED_IMAGE }}">

<meta property="og:site_name" content="{{ WEBSITE_NAME }}">
```

Checklist

- [ ] Title matches page
- [ ] Description reviewed
- [ ] Image publicly accessible
- [ ] URL correct
- [ ] Site name correct

---

# X (Twitter) Card Tags

```html
<meta name="twitter:card" content="summary_large_image">

<meta name="twitter:title" content="{{ PAGE_TITLE }}">

<meta name="twitter:description" content="{{ META_DESCRIPTION }}">

<meta name="twitter:image" content="{{ FEATURED_IMAGE }}">
```

Checklist

- [ ] Card type selected
- [ ] Title reviewed
- [ ] Description reviewed
- [ ] Image verified

---

# Favicons

Example

```html
<link rel="icon" href="/favicon.ico">

<link rel="apple-touch-icon" href="/apple-touch-icon.png">
```

Checklist

- [ ] Favicon available
- [ ] Apple icon available (if applicable)
- [ ] Icons render correctly

---

# Theme Color

Example

```html
<meta name="theme-color" content="#2563eb">
```

Review

- [ ] Matches brand
- [ ] Provides sufficient contrast

---

# Alternate Languages

For multilingual websites.

Example

```html
<link rel="alternate" hreflang="en" href="https://example.com/en">

<link rel="alternate" hreflang="hi" href="https://example.com/hi">
```

Checklist

- [ ] Language codes correct
- [ ] Alternate URLs verified
- [ ] Canonical strategy reviewed

---

# Structured Data

Include JSON-LD where appropriate.

Examples

- Organization
- WebSite
- Article
- BreadcrumbList
- FAQPage
- JobPosting

Reference:

```
templates/schema-template.json
```

---

# Metadata Checklist

Before publishing

- [ ] Title verified
- [ ] Meta description verified
- [ ] Canonical URL verified
- [ ] Robots meta reviewed
- [ ] Open Graph tags reviewed
- [ ] X Card tags reviewed
- [ ] Featured image tested
- [ ] Structured data validated

---

# Common Mistakes

Avoid

- Duplicate titles
- Duplicate descriptions
- Missing canonical URLs
- Broken images
- Placeholder text
- Incorrect URLs
- Misleading descriptions
- Metadata inconsistent with page content

---

# Related Documentation

- docs/seo.md
- docs/schema.md
- templates/schema-template.json
- checklists/on-page-seo.md
- checklists/schema-checklist.md

---

# Conclusion

Well-implemented metadata improves the discoverability, presentation, and consistency of web pages across search engines and social platforms.

Use this template as a starting point and adapt it to the specific requirements of your project.