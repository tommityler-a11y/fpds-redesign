# FPDS.gov Retirement Page Redesign

A complete redesign of the SAM.gov/fpds transition page, transforming dense program documentation into a scannable, task-oriented migration guide for the February 24, 2026 FPDS.gov decommissioning.

**📉 60% more concise** | **✨ Enhanced visual hierarchy** | **🎨 Color-coded pathways**

---

## 🔗 Links

- **Original page:** [https://sam.gov/fpds](https://sam.gov/fpds)
- **Live demo:** [https://YOUR-USERNAME.github.io/fpds-redesign/](https://YOUR-USERNAME.github.io/fpds-redesign/)



---

## 📁 Project Files

fpds-redesign/

├── index.html # Standalone demo with full USWDS styling 
├── drupal-content.html # CMS-ready HTML block for SAM.gov 
└── README.md # Project documentation


---

## 🎯 Project Goals

I redesigned this page to solve critical user experience problems identified in the original SAM.gov/fpds transition page:

### Problems with Original Page

- ❌ Dense paragraphs of technical documentation
- ❌ Poor information hierarchy
- ❌ Unclear calls-to-action
- ❌ Difficult to scan quickly
- ❌ Mixed audience guidance (public + federal users combined)

### Solutions in This Redesign

- ✅ **Task-first design** - "Where do I go?" decision matrix
- ✅ **Visual hierarchy** - Color-coded sections with icons
- ✅ **60% more concise** - Removed redundant content
- ✅ **Clear pathways** - Separate guidance for Search / Manage / API users
- ✅ **Dedicated federal section** - Isolated from public search guidance
- ✅ **Scannable layout** - Headlines, bullets, visual breathing room
- ✅ **Accessible** - ARIA labels, semantic HTML, keyboard navigation

---

## 🎨 Design System

Built with **USWDS 3.0** (U.S. Web Design System), the official design system for U.S. federal government websites.

### USWDS Components Used

- Alert boxes (info, warning, emergency)
- Buttons (primary & outline variants)
- Accordion component (FAQ section)
- Typography scale
- Grid system
- Utility classes for spacing and layout

### Design Principles Applied

- **Accessibility:** Section 508 and WCAG 2.1 AA compliant
- **Plain language:** Short sentences, active voice, defined acronyms
- **Mobile-responsive:** Works on all device sizes
- **Progressive disclosure:** FAQ accordion prevents overwhelming users

---

## 📋 Content Strategy

### Information Architecture

I restructured the page from program documentation to a wayfinding guide:

1. **Hero Alert** - Immediate deadline awareness (Feb 24, 2026)
2. **Where to Go** - Task-based decision matrix with visual cards
3. **Key Deadlines** - Timeline at a glance
4. **Important Reminders** - Login requirements & saved reports
5. **FAQ** - Collapsible answers to common questions
6. **Help Resources** - Links to support channels

### Content Reduction

- Original: ~2,400 words
- Redesign: ~950 words
- Reduction: 60% shorter while maintaining all critical information

---

## 🚀 Live Demo

The redesign is hosted on GitHub Pages at the link above. The `index.html` file includes all USWDS CSS/JS for a fully functional standalone demo.

---

## 📝 Drupal CMS Implementation

### Purpose of `drupal-content.html`

This file contains production-ready HTML that can be pasted directly into SAM.gov's Drupal CMS as a content block.

### Current Implementation Blocker

The Drupal version requires either:

**Option 1: Expand Basic HTML text format**

Allow these additional classes in the Basic HTML filter:

**Tags to add:**
- `<div>` with classes: `grid-row`, `grid-gap-2`, `tablet:grid-col-6`, `desktop:grid-col-4`, `margin-bottom-2`, `margin-top-2`, `bg-primary-lighter`, `border`, `padding-2`, `padding-3`
- `<span>` with classes: `text-primary`, `text-secondary`, `text-base-dark`

**Tags to expand:**
- `<p>` add: `usa-alert`, `usa-alert--info`, `border-left-05`, `border-primary`, `padding-left-2`, `margin-bottom-2`, `bg-primary-lighter`
- `<strong>` add: `text-primary`, `text-secondary`, `text-base-dark`
- `<ul>` and `<ol>` add: `margin-left-3`, `margin-top-2`, `usa-list`

**Option 2: Grant Full HTML access**

If you're a trusted content creator, your Drupal admin can grant access to the Full HTML text format, which would allow all USWDS utility classes without configuration changes.

---

## 🔍 Content Accuracy

All content cross-referenced with:

- Official [sam.gov/fpds](https://sam.gov/fpds) page
- GSA internal team communications
- FPDS decommissioning announcements
- SAM.gov migration documentation

### What's Ending February 24, 2026

- ✅ FPDS public search (ezSearch)
- ✅ ContractDirectory.gov (ICD)
- ✅ FPDS login access

### What Continues Beyond February 24

- ⏳ FPDS Atom Feed (retiring later in FY 2026)

---

## 👥 Target Audiences

This redesign serves four distinct user groups:

1. **Public users** - Searching for federal contract data
2. **Federal employees** - Managing contract awards in agency systems
3. **Developers/Integrators** - Using APIs for programmatic data access
4. **Contract Writing System vendors** - Migrating system integrations

Each group receives tailored guidance in the "Where to Go" decision matrix.

---

## 📊 Metrics & Testing

### Usability Improvements

- **Scan time:** Reduced from ~3 minutes to ~30 seconds (estimated)
- **Decision clarity:** Color-coded pathways eliminate confusion
- **Mobile readability:** Responsive grid adapts to all screen sizes

### Browser Testing

Tested on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## 🛠️ Technical Details

### Dependencies

- USWDS 3.0 (loaded via CDN in `index.html`)
- No build process required
- Pure HTML/CSS (no JavaScript frameworks)

### File Sizes

- `index.html`: ~15 KB
- `drupal-content.html`: ~12 KB

---

## 📧 Questions or Feedback?

If you have questions about this redesign or need clarification on implementation, please contact:

**tyler55@vt.edu**

---

## 📜 License

This project is in the **public domain** within the United States. Copyright and related rights in the work worldwide are waived through the CC0 1.0 Universal public domain dedication.

---

**Built for better government UX** 🇺🇸
