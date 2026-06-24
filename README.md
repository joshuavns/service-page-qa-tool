# Service / Product QA Checker

Standalone browser QA checker for Key Pages **Service / Product** drafts (Service Hub, Product Hub, Service Individual, Product Individual).

Part of Ring Ring Marketing's Key Pages toolset. Paste a generated page draft
(the section-tagged `[HERO]...[/HERO]` build spec, or load a `.docx`/`.txt`)
and the tool flags what needs fixing before it ships — meta tags, city-free
content, county cap, em-dashes, dollar amounts, phone placement, business-name
usage, anchor-text discipline, and page-type structure.

Checks are ported from the Key Pages Generator's `runQAChecks` engine. The tool
runs **entirely in your browser** — nothing is uploaded.

## Use it
- Hosted: enable GitHub Pages on this repo, then open the repo's Pages URL.
- Local: download `index.html` and open it in any browser.

Sibling tools: [home-page-qa-tool](https://github.com/joshuavns/home-page-qa-tool) · [service-page-qa-tool](https://github.com/joshuavns/service-page-qa-tool) · [about-us-page-qa-tool](https://github.com/joshuavns/about-us-page-qa-tool)
