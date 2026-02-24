# Tenders SA Publishers Hub
## Tenders-SA Publisher Widgets 

is a collection of freely embeddable data components powered by the Tenders-SA.org Publishers Hub. This repository provides the source code, integration guides, and documentation for bloggers, news sites, trade publications, and developers who want to embed live South African government procurement data directly onto their platforms.

Data is aggregated from official eTenders portals and updated hourly—requiring no API keys, no accounts, and no backend configuration.


🗺️ Provincial Tender Heatmap

What it does: Displays a live, color-coded map of South Africa showing the real-time distribution of government tender activity across all nine provinces. Darker provinces signal higher tender density.

Best for: Construction portals, policy blogs, and chamber of commerce websites.

🏆 Tender Award Winners Feed

What it does: A live, scrolling stream of recently awarded South African government contracts. Displays the winning company name, contract value, awarding department, and province.

Best for: News sites, investigative journalism portals, and business information hubs.

📊 Top Companies Leaderboard

What it does: Ranks South African businesses by the number of government tenders awarded within a chosen sector (e.g., ICT, Agriculture, Construction) or province.

Best for: Trade associations, competitive intelligence blogs, and finance news.

📈 Sector Tender Trends

What it does: Visualizes the volume and value of government tender opportunities across different industries over time to reflect spending patterns.

Best for: Sector-specialist blogs and magazines (e.g., tracking infrastructure or IT spending).


## Integration Methods

No-Code iFrame / HTML Snippet: The standard <iframe src="..."> approach for quick integration on CMS platforms like WordPress, Wix, or Shopify.

Pure JavaScript / Node.js SDK: The <div data-tendersa-widget data-type="heatmap"></div> coupled with the async script tag (tendersa-widget.js).

React/Next.js Component: (Mentioning the upcoming @tenderssa/widget npm package).

RSS Feeds: Documentation on how to syndicate the XML/RSS 2.0 feeds by province or category (using tools like Feedzy for WordPress).

REST API: Quick reference to public GET endpoints like /api/widgets/sector-trends and /api/widgets/top-companies for developers who want to build custom UI.

## Quick Start Guide (Draft for README)

Give developers a fast copy-paste solution right in the repo.

HTML
<div data-tendersa-widget data-type="heatmap"></div>

<script src="https://tenders-sa.org/tendersa-widget.js" async defer></script>
