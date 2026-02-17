# The Citizen — Interactive Article Visuals

Interactive data visualizations and civic tools accompanying investigative reporting from [**The Citizen**](https://thecitizentexas.substack.com), an independent accountability journalism publication based in Willow Park, Texas.

## About The Citizen

The Citizen covers municipal government, economic development, and public finance in Parker County and West Fort Worth. Our reporting empowers residents with practical tools and knowledge to engage meaningfully with local government decisions — particularly around economic development incentives, zoning, and fiscal policy.

We believe public meetings are where decisions get ratified, but documents are where decisions actually get made. These interactive visuals are designed to help citizens read between the lines.

## What's in This Repository

This repo hosts standalone, interactive HTML visuals that accompany our Substack articles. Each file is self-contained — no build tools, no frameworks, no server required. Just open in a browser.

### Current Visuals

*This table updates automatically when HTML files are added or changed.*

<!-- VISUAL-INDEX-START -->
| File | Title | Description |
|------|-------|-------------|
| [`Maintenance_Backlog_Data_Review.html`](./Maintenance_Backlog_Data_Review.html) | Maintenance Backlog — Data Review | — |
| [`tax-base-interactive.html`](./tax-base-interactive.html) | Tax Base Impact Over Time Interactive | How shifting land use percentages compound into dramatically different fiscal outcomes over 15 years of incremental rezoning. |
| [`zoning-compounding-visuals.html`](./zoning-compounding-visuals.html) | How Zoning Decisions Compound Over Time | Interactive visuals showing how incremental rezoning decisions transform communities over time. Land use diagrams and tax base impact data. |
<!-- VISUAL-INDEX-END -->

## How to Use

**View online:** Visit the live site at `https://spen-hodge.github.io/thecitizen_visuals/`

**View locally:** Download `index.html` and open it in any modern browser. Everything is self-contained — fonts load from Google Fonts, and all data, styles, and interactivity are built into the single file.

**Embed on a website:** Use an iframe pointing to the GitHub Pages URL:
```html
<iframe src="https://spen-hodge.github.io/thecitizen_visuals/" width="100%" height="800" frameborder="0"></iframe>
```

**Share a visual:** Link directly to the GitHub Pages URL from social media, newsletters, or other publications. Attribution to The Citizen is required under the license.

## For Civic Groups and Other Journalists

These visuals are designed to be shared. If you're a civic organization, neighborhood association, school, or journalist covering similar issues in your own community, you're welcome to use and adapt these materials under the terms of the license below. We just ask that you credit The Citizen and don't use them commercially.

If you'd like to collaborate or have questions about the data behind any visual, reach out via [The Citizen on Substack](https://thecitizentexas.substack.com).

## Data Sources

Our visuals draw on primary public records and recognized professional standards, including:

- Texas Comptroller of Public Accounts — Property tax system data
- Parker County Appraisal District — Property value records
- Texas Local Government Code — Municipal zoning and finance authority
- GFOA (Government Finance Officers Association) — Municipal finance best practices
- APA (American Planning Association) — Planning and zoning standards
- Lincoln Institute of Land Policy — Land use policy research
- NCTCOG (North Central Texas Council of Governments) — Regional planning data

Hypothetical scenarios are clearly labeled as illustrative. Source documentation is cited in each visual and its accompanying article.

## Technical Details

All visuals are built as single-file HTML pages with:

- **No dependencies** beyond Google Fonts (DM Sans / DM Serif Display)
- **No build step** — plain HTML, CSS, and vanilla JavaScript
- **Responsive design** — works on desktop and mobile
- **Brand-consistent styling** — The Citizen's color palette (Poppy #D93833, Indigo Dye #33425C, Jet #373435) and typography throughout

## License

This work is licensed under [**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt these materials with appropriate credit to The Citizen. Commercial use is not permitted without written permission.

See [LICENSE](./LICENSE) for full terms.

---

*The Citizen is an independent, reader-supported publication. If you find these tools useful, consider [subscribing](https://thecitizentexas.substack.com).*
