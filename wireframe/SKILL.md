---
name: wireframe
description: Create UI wireframes and mockups using drawio XML format with platform-specific UI component libraries. Best for web page layouts, iOS/Android mobile app mockups, and Bootstrap-based designs. Built on drawio with mockup-specific stencils. NOT for simple flowcharts (use mermaid) or data visualization (use vega).
metadata:
  author: Wireframe diagrams are powered by Markdown Viewer — the best multi-platform Markdown extension (Chrome/Edge/Firefox/VS Code) with diagrams, formulas, and one-click Word export. Learn more at https://docu.md
---

# UI Wireframe & Mockup Generator

**Quick Start:** Choose platform (Web/iOS/Android) → Add UI components from stencil library → Arrange in screen layout → Add navigation flows → Wrap in ` ```drawio ` fence.

> ⚠️ **IMPORTANT:** Always use ` ```drawio ` code fence. NEVER use ` ```xml ` — it will NOT render as a diagram.

## Critical Rules

> 🔗 **This is a drawio-derived skill.** All structure, layout, and edge routing rules inherit from [drawio SKILL.md](../drawio/SKILL.md). Read the base rules first.

**Wireframe-specific additions:**
- Check [stencils/README.md](../drawio/stencils/README.md) for exact UI stencil names
- Use consistent spacing: 10px for tight, 20px for normal, 40px for sections
- Mobile screens: iPhone 375×812, Android 360×800 (logical pixels)
- Web wireframes: 1200px or 1440px width for desktop

## Wireframe Types

| Type | Purpose | Stencil Library | Example |
|------|---------|-----------------|---------|
| Web Wireframe | Desktop/responsive web layouts | `mxgraph.mockup.*` (104 components) | [web-landing-page.md](examples/web-landing-page.md) |
| iOS Mockup | iPhone/iPad app screens | `mxgraph.ios7.*` (168 icons) | [ios-app-login.md](examples/ios-app-login.md) |
| Android Mockup | Android phone/tablet screens | `mxgraph.android.*` (49 components) | [android-app-list.md](examples/android-app-list.md) |
| Dashboard | Admin panels, data dashboards | `mxgraph.mockup.*` | [dashboard-admin.md](examples/dashboard-admin.md) |
