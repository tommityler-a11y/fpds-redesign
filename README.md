# FPDS.gov Retirement Page Redesign

## 🎯 Project Overview

This is a complete redesign of the **[SAM.gov/fpds transition page](https://sam.gov/fpds)**, rebuilt from the ground up to help users navigate the FPDS.gov decommissioning on **February 24, 2026**.

The original page was text-heavy with poor information hierarchy. This redesign uses **USWDS 3.0 components**, **UX best practices**, and **plain language** to create a scannable, task-oriented migration guide.

**📉 60% shorter** | **✨ Better visual hierarchy** | **🎨 Color-coded pathways**

---

## 🔗 Links

- **Original page:** [https://sam.gov/fpds](https://sam.gov/fpds)
- **Live redesign:** [https://YOUR-USERNAME.github.io/fpds-redesign/](https://YOUR-USERNAME.github.io/fpds-redesign/)

*(Replace `YOUR-USERNAME` with your GitHub username after deployment)*

---

## 📁 Repository Contents

fpds-redesign/ ├── index.html # GitHub Pages version (standalone, full USWDS styling) ├── drupal-content.html # Drupal-ready HTML block (for SAM.gov CMS) └── README.md # This file


---

## ✨ Key Improvements

### Before (Original)

- ❌ Dense paragraphs of technical documentation
- ❌ Poor information hierarchy
- ❌ Unclear calls-to-action
- ❌ Difficult to scan quickly
- ❌ Mixed audience (public + federal users)

### After (Redesign)

- ✅ **Task-first design** - "Where do you need to go?"
- ✅ **Visual hierarchy** - Color-coded sections with icons
- ✅ **60% more concise** - Removed redundant content
- ✅ **Clear decision matrix** - Search / Manage / API paths
- ✅ **Dedicated federal user section** - Separated from public search
- ✅ **Scannable layout** - Headlines, bullets, visual breaks
- ✅ **Accessible** - ARIA labels, semantic HTML, keyboard navigation

---

## 🎨 Design System

Built with **USWDS 3.0** (U.S. Web Design System):

- Official design system for U.S. federal government websites
- Accessibility compliant (Section 508, WCAG 2.1 AA)
- Mobile-responsive grid system
- Consistent typography and spacing

### Components Used

- Alert boxes
- Buttons (primary & outline variants)
- Accordion (FAQ)
- Typography scale
- Utility classes for spacing and layout

---

## 📋 Content Strategy

### Information Architecture

1. **Hero Alert** - Immediate deadline awareness
2. **Where to Go** - Task-based decision matrix
3. **Key Deadlines** - Timeline at a glance
4. **Important** - Login requirements & saved reports
5. **FAQ** - Collapsible answers to common questions
6. **Help** - Links to support resources

### Plain Language Principles

- Short sentences (avg. 15-20 words)
- Active voice
- Removed jargon where possible
- Defined acronyms on first use
- Scannable bullets instead of paragraphs

---

## 🚀 Deployment Instructions

### GitHub Pages Setup

1. **Create a new repository:**
   - Go to github.com
   - Click the + button (top right) → New repository
   - Name it `fpds-redesign`
   - Make it Public
   - Check "Add a README file"
   - Click Create repository

2. **Upload your files:**
   - Click "Add file" → "Upload files"
   - Drag and drop: `index.html`, `drupal-content.html`, `.gitignore`
   - Commit changes

3. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save
   - Your site will be live at: `https://YOUR-USERNAME.github.io/fpds-redesign/`

4. **Update this README:**
   - Replace `YOUR-USERNAME` with your actual GitHub username in the Links section above

---

## 📝 Drupal Implementation

### Current Blocker

The `drupal-content.html` file is ready to paste into SAM.gov's Drupal CMS, but requires:

1. **HTML source access** - Ability to enter raw HTML (not just WYSIWYG editor)
2. **Expanded text format** - USWDS utility classes must be allowed in Basic HTML format

### Required USWDS Classes

### Required USWDS Classes

The following classes need to be added to Drupal's Basic HTML text format filter:

**New tags:**
Expand existing tags:

<p> add: usa-alert usa-alert--info border-left-05 border-primary padding-left-2 margin-bottom-2 bg-primary-lighter
<strong> add: text-primary text-secondary text-base-dark
<ul> <ol> add: margin-left-3 margin-top-2 usa-list
Alternative: Full HTML Access
If the requester is a trusted content creator, granting access to the Full HTML text format would solve both issues without requiring text format configuration changes.

🔍 Sources & Accuracy
Content cross-referenced with:

Official SAM.gov/fpds page
GSA internal team communications
FPDS decommissioning announcements
SAM.gov migration documentation
What's Ending February 24, 2026
✅ FPDS public search (ezSearch)
✅ ContractDirectory.gov (ICD)
✅ FPDS login access
What Continues (Ending Later)
⏳ FPDS Atom Feed (retiring later in FY 2026)
👥 Target Audiences
Public users - Searching for contract data
Federal employees - Managing contract awards
Developers/Integrators - Using APIs for data access
Contract Writing System vendors - Migrating integrations
📧 Questions or Feedback?
Contact: tyler55@vt.edu

📜 License
This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the CC0 1.0 Universal public domain dedication.

Built with ❤️ for better government UX

