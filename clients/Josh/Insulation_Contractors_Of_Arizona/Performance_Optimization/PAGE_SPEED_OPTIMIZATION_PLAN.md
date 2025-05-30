# Page Speed Optimization Plan for AZ Foam Website
**Created:** May 30, 2025  
**Target Site:** https://azfoam.netlify.app/  
**Current Performance Score:** 74/100  
**Target Performance Score:** 90+/100

## 📊 Current Issues Analysis

### Critical Issues (High Priority)
1. **Render Blocking Requests** (3,630ms impact)
   - Netlify CSS files blocking initial render
   - Google Fonts loading synchronously
   - Large CSS bundles in critical path

2. **Image Delivery** (52 KB savings potential)
   - Oversized images for display dimensions
   - Missing responsive image optimization
   - No lazy loading implementation

3. **Largest Contentful Paint (LCP)** - 5.3s (Poor)
   - Target: < 2.5s for good score
   - Current impact: User sees blank page too long

### Medium Priority Issues
4. **DOM Size** (540 elements)
   - Excessive DOM depth (13 levels)
   - Most complex element: div.particles with 24 children
   - Target: < 450 elements, < 12 depth

5. **Network Dependency Tree** (599ms critical path)
   - Long chains of dependent resources
   - Unoptimized loading order

6. **Speed Index** - 4.5s
   - Target: < 3.4s for good score

### Low Priority Issues
7. **Long Main Thread Tasks** (90ms)
   - Minor JavaScript execution delays
   - Target: < 50ms per task

## 🎯 Optimization Strategy

### Phase 1: Critical Render Path (Week 1) - IMMEDIATE
**Goal:** Reduce FCP from 2.7s to < 1.5s and LCP from 5.3s to < 2.5s

#### Task 1.1: CSS Optimization ✅ Status: COMPLETED (May 30, 2025)
- [x] Identify and extract critical CSS for above-the-fold content
- [x] Inline critical CSS in `<head>`
- [x] Defer non-critical CSS loading
- [x] Minify all CSS files
- [x] Combine multiple CSS files where possible

**Implementation Files:**
- Created `critical.css` with only above-fold styles ✅
- Updated `base.njk` to inline critical CSS ✅
- Implemented CSS loading strategy with preload ✅

#### Task 1.2: Font Optimization ✅ Status: IN PROGRESS
- [x] Preload critical fonts
- [x] Use font-display: swap
- [ ] Subset fonts to reduce size
- [ ] Self-host Google Fonts if possible

**Next Steps:**
- Create font subset with only used characters
- Download and self-host Inter font family
- Implement font loading observer

#### Task 1.3: JavaScript Defer/Async ✅ Status: NOT STARTED
- [ ] Add defer attribute to non-critical scripts
- [ ] Move scripts to bottom of body
- [ ] Remove unused JavaScript

### Phase 2: Image Optimization (Week 1-2) - HIGH PRIORITY
**Goal:** Reduce image payload by 50%+

#### Task 2.1: Responsive Images ✅ Status: NOT STARTED
- [ ] Implement srcset for all images
- [ ] Create multiple sizes: 400w, 800w, 1200w
- [ ] Use WebP format with fallbacks
- [ ] Add proper width/height attributes

#### Task 2.2: Lazy Loading ✅ Status: NOT STARTED
- [ ] Implement native lazy loading (loading="lazy")
- [ ] Prioritize above-fold images
- [ ] Add intersection observer for advanced cases

#### Task 2.3: Image Compression ✅ Status: NOT STARTED
- [ ] Compress existing images more aggressively
- [ ] Use appropriate formats (WebP for photos, SVG for graphics)
- [ ] Implement responsive breakpoints

### Phase 3: DOM Optimization (Week 2) - MEDIUM PRIORITY
**Goal:** Reduce DOM elements below 450

#### Task 3.1: Simplify Structure ✅ Status: NOT STARTED
- [ ] Remove unnecessary wrapper divs
- [ ] Consolidate similar elements
- [ ] Use CSS Grid/Flexbox instead of nested divs
- [ ] Remove particles animation or optimize it

#### Task 3.2: Component Refactoring ✅ Status: NOT STARTED
- [ ] Audit each component for DOM efficiency
- [ ] Combine redundant elements
- [ ] Use pseudo-elements instead of extra divs

### Phase 4: Resource Loading (Week 2-3) - MEDIUM PRIORITY
**Goal:** Optimize network waterfall

#### Task 4.1: Resource Hints ✅ Status: NOT STARTED
- [ ] Add preconnect for external domains
- [ ] Add prefetch for likely next pages
- [ ] Implement resource priorities

#### Task 4.2: Bundle Optimization ✅ Status: NOT STARTED
- [ ] Code split large bundles
- [ ] Remove unused CSS/JS
- [ ] Implement tree shaking

### Phase 5: Performance Monitoring (Ongoing)
**Goal:** Maintain performance gains

#### Task 5.1: Automated Testing ✅ Status: NOT STARTED
- [ ] Set up Lighthouse CI in deployment pipeline
- [ ] Create performance budgets
- [ ] Alert on regressions

## 📋 Implementation Checklist

### Immediate Actions (Today - May 30, 2025)
- [x] Create optimization plan
- [x] Extract critical CSS for homepage ✅
- [x] Inline critical CSS in base template ✅
- [x] Defer non-critical stylesheets ✅

### Week 1 (May 30 - June 6, 2025)
- [ ] Complete Phase 1: Critical Render Path (90% done)
- [ ] Start Phase 2: Image Optimization
- [ ] Implement font optimization
- [ ] Deploy and test improvements

### Week 2 (June 7 - June 13, 2025)
- [ ] Complete Phase 2: Image Optimization
- [ ] Complete Phase 3: DOM Optimization
- [ ] Start Phase 4: Resource Loading

### Week 3 (June 14 - June 20, 2025)
- [ ] Complete Phase 4: Resource Loading
- [ ] Set up performance monitoring
- [ ] Final optimizations and testing

## 📈 Success Metrics

| Metric | Current | Target | Status |
|--------|---------|--------|--------|
| Performance Score | 74 | 90+ | 🔴 |
| First Contentful Paint | 2.7s | < 1.5s | 🔴 |
| Largest Contentful Paint | 5.3s | < 2.5s | 🔴 |
| Speed Index | 4.5s | < 3.4s | 🟡 |
| Total Blocking Time | 0ms | < 200ms | 🟢 |
| Cumulative Layout Shift | 0 | < 0.1 | 🟢 |

## 🛠️ Tools & Resources

- **Critical CSS Generator:** https://github.com/addyosmani/critical
- **Image Optimization:** Sharp, ImageOptim
- **Performance Testing:** Lighthouse CI, WebPageTest
- **Bundle Analysis:** Webpack Bundle Analyzer

## 📝 Progress Log

### May 30, 2025
- **4:35 PM** - Created optimization plan
- **4:37 PM** - Created critical.css file with essential above-fold styles
- **4:39 PM** - Updated base.njk with inline critical CSS and deferred loading
- **Status:** Critical CSS optimization complete, moving to font optimization

## 📝 Notes

- Priority on mobile performance (most users)
- Maintain visual quality while optimizing
- Test on real devices, not just tools
- Document all changes for future reference

---

**Last Updated:** May 30, 2025 4:40 PM  
**Updated By:** Echo (SEO & Brand Strategist)