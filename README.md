# Awesome-Drag-And-Drop-Website-Builder

# Top Drag-and-Drop Website Builder Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Visual Page Design, No-Code Site Construction & Self-Hosted Alternatives*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Drag-and-Drop Website Builders**. These tools help users design and publish websites visually—without writing code—covering everything from all-in-one hosted builders to open-source frameworks you can self-host and extend.

**Examples** include Wix, Squarespace, Webflow, Zoho Website Builder, WordPress (with Elementor), Silex, Webstudio, GrapesJS, and VvvebJs (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted visual site building, open-source page editors, and community-driven website frameworks—ideal for developers, agencies, and organizations seeking data sovereignty and freedom from per-site subscriptions. The open-source landscape splits into two distinct categories: **ready-made visual builders** (Silex, Webstudio, Publii) you can install and use, and **builder frameworks** (GrapesJS, VvvebJs) you embed into your own product [citation:1][citation:3].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Wix](https://www.wix.com/)** | All-in-one hosted website builder with drag-and-drop editor, templates, and app market. | Quote-only (tiered by features) | **Free plan** available with Wix ads; premium plans for custom domain |
| **[Squarespace](https://www.squarespace.com/)** | Design-focused hosted builder with polished templates and integrated commerce. | Quote-only (tiered by features) | **14-day free trial** available |
| **[Webflow](https://webflow.com/)** | Visual development platform with CSS-level control, CMS, and hosting. | Quote-only (Site plans from ~$15/month) | **Free Starter plan** (2 pages, prototyping only) |
| **[Zoho Website Builder](https://www.zoho.com/)** | Website builder within the Zoho ecosystem (limited public information available). | Contact Zoho for pricing | Contact vendor |
| **[WordPress + Elementor](https://elementor.com/)** | Self-hosted CMS (WordPress) with the most popular drag-and-drop page builder plugin (Elementor). | Free (WordPress + Elementor core); Elementor Pro from ~$59/year | **Free**: WordPress core and Elementor free tier with basic widgets |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Silex](https://github.com/silexlabs/Silex)** | [![Stars](https://img.shields.io/github/stars/silexlabs/Silex?style=social&color=white)](https://github.com/silexlabs/Silex/stargazers) | **The most complete open-source visual builder for static sites and a direct Webflow alternative.** AGPL-3.0, self-hostable via Docker or Node.js. Drag-and-drop page building with **HTML, CSS, and JS editors**, plus a GrapesJS-based visual editor. Outputs **clean static HTML** you can host anywhere. Integrates with WordPress, Strapi, or any GraphQL API as a headless CMS. Maintained by the non-profit Silex Labs—no investors, no exit strategy, no premium tier [citation:1][citation:8]. **Best for agencies and designers wanting visual building without vendor lock-in.** |
| **[Webstudio](https://github.com/webstudio-is/webstudio)** | [![Stars](https://img.shields.io/github/stars/webstudio-is/webstudio?style=social&color=white)](https://github.com/webstudio-is/webstudio/stargazers) | **The closest open-source experience to Webflow's modern canvas.** Self-hostable, component-driven visual builder with **CSS-level control** and a real community of designers migrating from subscription tooling. Connects to any headless CMS (WordPress, Ghost, Directus) and supports **MCP-based agent workflows**. **Trade-off**: intentionally a frontend builder rather than an integrated CMS—content-heavy sites need a separate system, creating more integration work than Webflow's managed stack [citation:1][citation:10]. **Best for designers who want Webflow-style editing without per-site subscriptions.** |
| **[GrapesJS](https://github.com/GrapesJS/grapesjs)** | [![Stars](https://img.shields.io/github/stars/GrapesJS/grapesjs?style=social&color=white)](https://github.com/GrapesJS/grapesjs/stargazers) | **The leading framework for building your own page builder.** BSD-3-Clause (permissive for commercial embedding). Generates HTML, CSS, and JavaScript with pluggable storage. **Not a ready-to-use website builder**—it's the foundation most teams reach for when shipping a SaaS product that needs a drag-and-drop editor inside it [citation:1][citation:3]. **Best for developers embedding an editor in their own product.** |
| **[VvvebJs](https://github.com/givanz/VvvebJs)** | [![Stars](https://img.shields.io/github/stars/givanz/VvvebJs?style=social&color=white)](https://github.com/givanz/VvvebJs/stargazers) | **Bootstrap-native drag-and-drop page builder library.** AGPL-3.0, vanilla JavaScript with no dependencies or build tools. Outputs Bootstrap-compatible HTML/CSS. Integrates with the **Vvveb CMS** for full website management (optional PHP/MySQL backend) [citation:1][citation:7]. **Best for teams already standardized on Bootstrap** who want a turnkey builder or a library they can extend. |
| **[Publii](https://github.com/GetPublii/Publii)** | [![Stars](https://img.shields.io/github/stars/GetPublii/Publii?style=social&color=white)](https://github.com/GetPublii/Publii/stargazers) | **Desktop static site builder with no server to secure.** Builds the site locally and uploads to any host. **No database, no login page, no server-side attack surface**—the entire CMS attack surface simply doesn't exist. **Trade-off**: editing happens on one machine unless you sync files manually, ruling out collaborative teams but suiting solo owners perfectly [citation:1]. **Best for individuals who want a static site and zero server administration.** |
| **[Blocks](https://github.com/blocks/blocks)** | [![Stars](https://img.shields.io/github/stars/blocks/blocks?style=social&color=white)](https://github.com/blocks/blocks/stargazers) | **JSX-based no-code visual website builder.** Assemble pages using a drag-and-drop interface with pre-designed JSX component blocks. Direct fit for building websites without writing code, though it does not clearly advertise support for static site export or self-hosted deployment [citation:3][citation:7]. **Best for React/JSX teams wanting a component-block builder.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[MaxiBlocks](https://github.com/maxi-blocks/maxi-blocks)** | [![Stars](https://img.shields.io/github/stars/maxi-blocks/maxi-blocks?style=social&color=white)](https://github.com/maxi-blocks/maxi-blocks/stargazers) | **Free, open-source WordPress page builder with 17,000+ design assets.** GPL-3.0. 19 blocks with visual style controls, 542 patterns, 14,417 icons, 100 style cards, and one-click starter sites. **Everything works from day one—no paywalled features.** Extends the Gutenberg block editor rather than replacing it [citation:2]. **Best for WordPress users wanting a capable free builder without Elementor Pro pricing.** |
| **[Microweber](https://github.com/microweber/microweber)** | [![Stars](https://img.shields.io/github/stars/microweber/microweber?style=social&color=white)](https://github.com/microweber/microweber/stargazers) | **Open-source website builder and CMS with drag-and-drop editing.** Self-hostable, with paid plans starting at $10/month for managed hosting. Positioned as a small-business website builder with e-commerce capabilities [citation:12]. **Best for small businesses wanting a self-hosted builder with CMS built in.** |

**Frameworks for building custom systems**: Choose **Silex** for a ready-made static site builder with visual editing and clean HTML output , **Webstudio** for Webflow-style canvas editing with headless CMS integration , **GrapesJS** or **VvvebJs** for embedding a builder into your own product , and **Publii** for zero-server static site building —all without per-site subscription fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Website builders may handle customer data, forms, and e-commerce transactions; enforce appropriate security controls and compliance with applicable regulations.
- **Open-source website builders split into two distinct use cases.** **Ready-made builders** (Silex, Webstudio, Publii) let you design and publish sites visually—Silex outputs static HTML , Webstudio requires a separate CMS for content-heavy sites , and Publii is desktop-only . **Builder frameworks** (GrapesJS, VvvebJs) are libraries for embedding editors into products—not standalone site builders . **Licensing matters**: Silex and VvvebJs are **AGPL-3.0** (network-use obligations if you offer modified software as a service) , GrapesJS is **BSD-3-Clause** (permissive) , and MaxiBlocks is **GPL-3.0** . **WordPress with a builder plugin** is the most capable open-source option by ecosystem breadth, but requires assembling multiple plugins from different vendors [citation:1]. Validate licensing compatibility and your actual deployment model before committing.

---

**Made for designers, developers, agencies, and organizations building websites without code.**  
Let's make drag-and-drop website building more open, portable, and user-owned.
