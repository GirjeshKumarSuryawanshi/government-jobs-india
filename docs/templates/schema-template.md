# Schema Template

## Overview

This JSON-LD template provides a reusable starting point for implementing structured data on a website.

It includes commonly used Schema.org types:

- Organization
- WebSite
- WebPage
- BreadcrumbList
- Article

Replace every placeholder enclosed in `{{ }}` with values appropriate for your website.

---

# Placeholders

| Placeholder | Description |
|-------------|-------------|
| {{SITE_URL}} | Website homepage URL |
| {{PAGE_URL}} | Canonical page URL |
| {{PAGE_TITLE}} | Page title |
| {{META_DESCRIPTION}} | Meta description |
| {{ORGANIZATION_NAME}} | Organization name |
| {{LOGO_URL}} | Public logo URL |
| {{AUTHOR_NAME}} | Author name |
| {{CATEGORY_NAME}} | Category title |
| {{CATEGORY_URL}} | Category URL |
| {{DATE_PUBLISHED}} | ISO 8601 publication date |
| {{DATE_MODIFIED}} | ISO 8601 modification date |

---

# Validation

Before deployment:

- Validate JSON syntax.
- Confirm structured data matches visible page content.
- Review required properties for each schema type.
- Test using appropriate structured data validation tools.

---

# Related Files

See the `examples/` directory for individual implementations such as:

- `Organization.json`
- `WebSite.json`
- `Article.json`
- `Breadcrumb.json`
- `FAQPage.json`
- `JobPosting.json`

These files demonstrate complete examples for specific schema types.