---
name: Bug report
about: "## Template Purpose  Tracks UI/styling issues in the AI Auto system to improve
  automation, product display, and user experience. Ensures consistent input for smarter
  system diagnostics."
title: 'function generateBugTitle({ bugType, component, device }) {   const timestamp
  = new Date().toISOString().split(''T'')[0]; // YYYY-MM-DD   const type = bugType
  || "Styling Issue";   const part = component || "Unknown Module";   const platform
  = device || "All Devices";    return `[${timestamp}] ${type} in ${part} on ${platform}`;
  }  // Example Usage const defaultTitle = generateBugTitle({   bugType: "UI Glitch",   component:
  "Product Upload Panel",   device: "Mobile Safari" });  console.log(defaultTitle);
  // Output: [2025-03-21] UI Glitch in Product Upload Panel on Mobile Safari'
labels: ''
assignees: BernabeLilBee

---

M# Bug Report – AI Auto System Styling/UI

## Bug Title:
[Short summary of the issue, e.g., "Product card spacing breaks on mobile view"]

---

## Bug Type:
- [ ] Styling/Layout
- [ ] Media Upload Issue
- [ ] Pricing Calculation
- [ ] Product Sync
- [ ] Dropship Integration

---

## Priority:
- [ ] Low
- [ ] Medium
- [ ] High
- [ ] Critical (Blocks workflow)

---

## Affected Area:
[Which part of the system? e.g., “Product Upload Module,” “Price Sync,” etc.]

## Browser/Device:
[e.g., Chrome 123, iPhone 14 Pro Safari, etc.]

## Description:
[What’s the issue? Explain what you expected to happen, and what actually happened.]

---

## Steps to Reproduce:
1. Go to [section or URL]
2. Click [action]
3. [What happens]
4. [What should’ve happened]

---

## Screenshot(s):
![Upload Bug Screenshot Here]()

## Video Upload (if needed):
[Paste link or upload a demo]

---

## File Upload Issue (if any):
- [ ] Image fails to load
- [ ] Video doesn’t preview
- [ ] File size/format error

---

## Automation Affected:
[Is any automation not triggering because of this bug? Describe it.]

---

## Suggested Fix (Optional):
[If you see a solution — like CSS issue, missed condition, etc.]

---

## Notes:
[Anything else that helps replicate or diagnose the bug]
