# Core Web Vitals Checklist

## Introduction

Core Web Vitals are a set of performance metrics that measure the real-world user experience of a web page.

They focus on three key areas:

- Loading performance
- Interactivity
- Visual stability

This checklist helps developers and website owners review common optimizations before deployment and during ongoing maintenance.

> Performance improvements should always be validated with real measurements rather than assumptions.

---

# Core Web Vitals Overview

| Metric | Measures | Goal |
|---------|----------|------|
| Largest Contentful Paint (LCP) | Loading performance | ≤ 2.5 seconds |
| Interaction to Next Paint (INP) | Responsiveness | ≤ 200 ms |
| Cumulative Layout Shift (CLS) | Visual stability | ≤ 0.1 |

---

# Largest Contentful Paint (LCP)

Review:

- [ ] Largest content loads quickly.
- [ ] Server response time optimized.
- [ ] Hero images compressed.
- [ ] Images use modern formats where appropriate.
- [ ] Images have correct dimensions.
- [ ] Critical CSS optimized.
- [ ] Render-blocking resources minimized.
- [ ] Large JavaScript bundles reviewed.
- [ ] Above-the-fold content prioritized.

---

# Interaction to Next Paint (INP)

Review:

- [ ] JavaScript execution minimized.
- [ ] Long-running tasks reduced.
- [ ] Event handlers optimized.
- [ ] Third-party scripts reviewed.
- [ ] UI remains responsive during interaction.
- [ ] Form interactions tested.
- [ ] Navigation remains responsive.

---

# Cumulative Layout Shift (CLS)

Review:

- [ ] Images have width and height specified.
- [ ] Ads reserve space before loading.
- [ ] Embedded content reserves layout space.
- [ ] Fonts do not cause unexpected layout shifts.
- [ ] Dynamic content does not push visible elements unexpectedly.

---

# Images

Review:

- [ ] Images compressed.
- [ ] Appropriate dimensions.
- [ ] Responsive images implemented.
- [ ] Lazy loading used where appropriate.
- [ ] Decorative images optimized.

---

# Fonts

Review:

- [ ] Font files optimized.
- [ ] Font formats reviewed.
- [ ] Unused font weights removed.
- [ ] Font loading strategy reviewed.
- [ ] Fallback fonts configured.

---

# CSS

Review:

- [ ] Unused CSS removed.
- [ ] CSS minified.
- [ ] Critical CSS prioritized.
- [ ] Large CSS files reviewed.

---

# JavaScript

Review:

- [ ] Unused JavaScript removed.
- [ ] JavaScript minified.
- [ ] Code splitting considered.
- [ ] Deferred loading used where appropriate.
- [ ] Third-party scripts reviewed regularly.

---

# Server Performance

Review:

- [ ] HTTPS enabled.
- [ ] Compression enabled.
- [ ] Caching configured.
- [ ] Server response times monitored.
- [ ] Database queries optimized.
- [ ] CDN considered where appropriate.

---

# Caching

Review:

- [ ] Browser caching configured.
- [ ] Static assets cached.
- [ ] Cache headers reviewed.
- [ ] Cache invalidation strategy documented.

---

# Mobile Performance

Review:

- [ ] Mobile network tested.
- [ ] Touch interactions responsive.
- [ ] Images optimized for mobile.
- [ ] Tables remain usable.
- [ ] Navigation performs well on smaller screens.

---

# Accessibility

Performance improvements should not reduce accessibility.

Review:

- [ ] Semantic HTML preserved.
- [ ] Keyboard navigation functional.
- [ ] Contrast maintained.
- [ ] Images retain meaningful alt text.

---

# Third-Party Resources

Review:

- [ ] Analytics scripts reviewed.
- [ ] Advertising scripts reviewed.
- [ ] Social widgets reviewed.
- [ ] External libraries minimized.
- [ ] Unused integrations removed.

---

# Before Deployment

- [ ] Performance tested on desktop.
- [ ] Performance tested on mobile.
- [ ] Core Web Vitals measured.
- [ ] Large assets optimized.
- [ ] Lazy loading verified.
- [ ] Caching reviewed.

---

# Ongoing Monitoring

Review regularly:

- [ ] Loading performance.
- [ ] Interaction responsiveness.
- [ ] Layout stability.
- [ ] Broken resources.
- [ ] Large images.
- [ ] Third-party scripts.
- [ ] Server performance.

---

# Common Performance Issues

Avoid:

- Oversized images.
- Excessive JavaScript.
- Large CSS bundles.
- Render-blocking resources.
- Too many third-party scripts.
- Missing image dimensions.
- Layout shifts caused by dynamic content.

---

# Optimization Workflow

```text
Measure

↓

Identify Bottlenecks

↓

Optimize Assets

↓

Retest

↓

Deploy

↓

Monitor

↓

Repeat
```

---

# Related Documentation

- docs/seo.md
- checklists/technical-seo-checklist.md
- diagrams/seo-flow.md

---

# Conclusion

Core Web Vitals are part of a broader performance strategy focused on delivering a fast, stable, and responsive experience.

Measure performance regularly, prioritize improvements that benefit users, and monitor changes over time to ensure continued quality.